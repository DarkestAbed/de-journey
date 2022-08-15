# A primer on the journey of the data engineer
This is a first approach on the journey of the Data Engineer. The resources found here allow the student to take a quick look into the day-to-day life of the data engineer, the tools used, and the expected workload of a data engineer on any single company that has a data engineering team.

## Contents
* [Introduction](intro/intro_to_de.md)
* [Basic tools](basic_tools/)
    * [Linux and the Command Line](basic_tools/linux.md)
        * [Linux environments](basic_tools/linux.md#linux-environments)
        * [WSL](basic_tools/linux.md#wsl)
        * [macOS](basic_tools/linux.md#macos)
        * [Command line interfaces](basic_tools/linux.md#command-line-interfaces)
            * [Bash](basic_tools/linux.md#bash)
            * [zsh](basic_tools/linux.md#zsh)
            * [Other shells](basic_tools/linux.md#other-shells)
        * [Why not Windows?](basic_tools/why_not_win.md)
            * [Why not PowerShell?](basic_tools/why_not_win.md#why-not-powershell)
    * [Contenerization and productization](basic_tools/docker.md)
* A data engineer journey
    * Data engineer vs Cloud engineer
    * Data engineer vs Data analyst
    * Data engineer vs Data scientist
* Data loading and transformation (ETL/ELT) tools
    * CLI tools
        * cron
        * sqoop
        * Automation scripts
    * GUI tools
        * Local tools
            * SSIS
            * Datastage
            * Pentaho
            * Talend
        * Cloud tools
            * Azure Data Factory
            * Airflow & Google Cloud Composer
            * AWS Glue
            * Hevo
* Data processing tools
    * Old school tools
        * SQL
        * Data processing programming
            * Python
                * Vanilla
                * \+ NumPy
                * \+ Pandas
                * \+ Dask
                * And others
            * Scala
            * Other programming languages
    * Hadoop suite
        * Hive
        * Spark
        * Kafka
    * Databricks
    * Google Dataproc & Dataflow
    * Atomic processing
        * AWS Lambda
        * Azure Functions
        * Google Functions & Google Cloud Run
        * Scheduling tools for atomic processing
* Data security
* Data + DevSecOps: DataOps
* Case study