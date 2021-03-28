# Building a data pipeline for car information

## Database Design

![ERD](img/DWDB.png)

I have proceeded to create a simplistic database design following the snowflake schema methodology. In doing so we can utilize less disk space as a result of data normalization and therefore minimal data redundancy. This will help provide protection from data integrity issues. Maintenance is simple due to a smaller risk of data integrity violations and low level of data redundancy.

## Workflow

![Process](img/process.png)

This workflow diagram details a potential solution that will allow us to convert raw csv files into S3 buckets and then into a datawarehouse where our snowflake database design will reside. This will then allow us to set up AWS QuickSight to enable analysts access to quick insights.

## Software

### Tech Stack Required

## Initial Load

## Data Cleanup

## Security Protocols

## Scalability

## Analytics

## Notifications and Monitoring




