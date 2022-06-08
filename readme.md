# Introduction

##  What is Data Factory

DataSource  ==> Transform  ==> Destination
            Extract         Load
Database                        Database
Logs                            Blob/data lake

An Azure Data Factory instance uses JSON to describe each of its entities

-   Pipeline Properties

    -   name:   Specifies the name of the pipeline
    -   description: Specifies the text describing what the pipeline is used for
    -   activities: The pipeline can have one or more activities defined within it.
    -   parameters: The parameters property can have one or more parameters defined within the pipeline

### Activities

Activities represent a processing step in a pipeline. These are specific tasks that compose the overall pipeline

Execution Activities (Copy and Data Transform)

