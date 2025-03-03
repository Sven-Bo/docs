---
title: Connect to data sources
slug: /streamlit-community-cloud/get-started/deploy-an-app/connect-to-data-sources
---

# Connect data sources

Your app probably connects to some data source, and it's important to make sure that connection is secure. That data might just be a csv that you have in your GitHub repo, but in many cases it'll be a private data source you connect with via API, on a cloud service, or maybe in your company's VPN.

Streamlit has one primary way of securely connecting to private data:

- [Secrets management](/streamlit-community-cloud/get-started/deploy-an-app/connect-to-data-sources/secrets-management): securely store secrets like API keys and TOML files that you can then access as environment variables in your app.

We also have a series of guides on how to connect to:

<DataSourcesContainer>
<DataSourcesCard href="/knowledge-base/tutorials/databases/aws-s3">

<Image pure alt="screenshot" src="/images/databases/s3.png" />

<h5>AWS S3</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/bigquery">

<Image pure alt="screenshot" src="/images/databases/bigquery.png" />

<h5>BigQuery</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/deta-base">

<Image pure alt="screenshot" src="/images/databases/deta-base.png" />

<h5>Deta Base</h5>

</DataSourcesCard>

<DataSourcesCard href="https://blog.streamlit.io/streamlit-firestore/">

<Image pure alt="screenshot" src="/images/databases/firestore.png" />

<h5>Firestore (blog)</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/gcs">

<Image pure alt="screenshot" src="/images/databases/gcs.png" />

<h5>Google Cloud Storage</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/mssql">

<Image pure alt="screenshot" src="/images/databases/mssql.png" />

<h5>Microsoft SQL Server</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/mongodb">

<Image pure alt="screenshot" src="/images/databases/mongodb.png" />

<h5>MongoDB</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/mysql">

<Image pure alt="screenshot" src="/images/databases/mysql.png" />

<h5>MySQL</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/postgresql">

<Image pure alt="screenshot" src="/images/databases/postgresql.png" />

<h5>PostgreSQL</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/private-gsheet">

<Image pure alt="screenshot" src="/images/databases/gsheet.png" />

<h5>Private Google Sheet</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/public-gsheet">

<Image pure alt="screenshot" src="/images/databases/gsheet.png" />

<h5>Public Google Sheet</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/snowflake">

<Image pure alt="screenshot" src="/images/databases/snowflake.png" />

<h5>Snowflake</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/supabase">

<Image pure alt="screenshot" src="/images/databases/supabase.png" />

<h5>Supabase</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/tableau">

<Image pure alt="screenshot" src="/images/databases/tableau.png" />

<h5>Tableau</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/tidb">

<Image pure alt="screenshot" src="/images/databases/tidb.png" />

<h5>TiDB</h5>

</DataSourcesCard>

<DataSourcesCard href="/knowledge-base/tutorials/databases/tigergraph">

<Image pure alt="screenshot" src="/images/databases/tigergraph.png" />

<h5>TigerGraph</h5>

</DataSourcesCard>
</DataSourcesContainer>

<Note>

Trouble connecting to data? Need a different way to securely connect? Reach out on our [Community forum](https://discuss.streamlit.io) to chat through options!

</Note>
