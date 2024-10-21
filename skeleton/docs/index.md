## Component metadata

| Field Name               | Value                                                                                                                  |
|:-------------------------|:-----------------------------------------------------------------------------------------------------------------------|
| **Name**                 | ${{ values.name }}                                                                                                     |
| **Fully Qualified Name** | ${{ values.domainName }} - ${{ values.dataproductName }} - version ${{ dataProductMajorVersion }} - ${{ values.name }} |
| **Description**          | ${{ values.description }}                                                                                              |
| **Domain**               | ${{ values.domain }}                                                                                                   |
| **Data Product**         | ${{ values.dataproduct }}                                                                                              |
| **Identifier**           | ${{ values.identifier }}                                                                                               |
| **Development Group**    | ${{ values.developmentGroup }}                                                                                         |
| **Depends On**           | ${{ values.dependsOn }}                                                                                                |

## Snowflake deployment information

| Field Name     | Value                   |
|:---------------|:------------------------|
| **Database**   | ${{ values.database }}  |
| **Schema**     | ${{ values.schema }}    |
| **Table Name** | ${{ values.tableName }} |