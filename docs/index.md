![banner](./assets/logo_with_text.png)

---

# Geniusrise Ecosystem

Geniusrise is a modular, loosely-coupled AgentOps / MLOps framework designed for the era of Large Language Models, offering flexibility, inclusivity, and standardization in designing networks of AI agents.

It seamlessly integrates tasks, state management, data handling, and model versioning, all while supporting diverse infrastructures and user expertise levels. With its plug-and-play architecture, Geniusrise empowers teams to build, share, and deploy AI agent workflows across various platforms efficiently.

## Guides

---

### 🚀 <span style="color:#f34960">Getting Started</span>

---

1. 📘 [**Concepts**](guides/concepts.md) - <span style="color:#e667aa">Concepts of the framework, start here.</span>
2. 🏗️ [**Architecture**](guides/architecture.md) - <span style="color:#e667aa">Design and architecture of the framework.</span>
3. 🛠️ [**Installation**](guides/installation.md) - <span style="color:#e667aa">Installation and setup.</span>

### 💻 <span style="color:#f34960">Development</span>

---

1. 🏠 [**Local Experimentation**](guides/local.md) - <span style="color:#e667aa">Local setup and project creation.</span>
2. 🔄 [**Dev Cycle**](guides/dev_cycle.md) - <span style="color:#e667aa">Describes one full local development cycle.</span>
3. 📦 [**Packaging**](guides/packaging.md) - <span style="color:#e667aa">Packaging your application.</span>
4. 🚀 [**Deployment**](guides/deployment.md) - <span style="color:#e667aa">Deploying parts or whole of your application.</span>
<!-- 5. ⚙️ [**Workflow Ops**](guides/index.md) - <span style="color:#e667aa">Operations and management of workflows.</span>
5. 📊 [**Data Ops**](guides/index.md) - <span style="color:#e667aa">Operations and management of data.</span>
6. 🤖 [**Model Ops**](guides/index.md) - <span style="color:#e667aa">Operations and management of models.</span> -->

### 📚 <span style="color:#f34960">Reference</span>

---

1. 📄 [**YAML Structure**](guides/yaml.md) - <span style="color:#e667aa">Geniusfile structure and configuration.</span>
2. 🌐 [**CLI reference**](guides/cli.md) - <span style="color:#e667aa">Command line reference.</span>
3. 🎨 [**Project Templates**](guides/index.md) - <span style="color:#e667aa">Project templates for community plugins.</span>

### 🏃 Runners

| 🌐 **Runners**                              |                                       |                               |                                         |
| ------------------------------------------- | ------------------------------------- | ----------------------------- | --------------------------------------- |
| 🟢 [k8s deployment](core/k8s_deployment.md) | 🟤 [k8s service](core/k8s_service.md) | 🟡 [k8s job](core/k8s_job.md) | 🟠 [k8s cron job](core/k8s_cron_job.md) |
| 🟧 [k8s pods](core/k8s_base.md)             | 🟦 [Apache Airflow](core/airflow.md)  | 🔴 [Docker](core/docker.md)   | 🟣 [Docker Swarm](core/docker_swarm.md) |

<!-- |                                       | 🟣 [~Apache Airflow~](guides/index.md) | 🔵 [~AWS Fargate~](guides/index.md) | 🟥 [~AWS ECS~](guides/index.md)         | 🟩 [~AWS Batch~](guides/index.md) | | -->

### 🤖 Models

#### Inference APIs

| 🌐 **Local & Huggingface**                              |                                                                    |                                                         |
| ------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------- |
| 🟢 [Language Model](text/api/language_model.md)         | 🟣 [Named Entity Recognition](text/api/ner.md)                     | 🟡 [Question Answering](text/api/question_answering.md) |
| 🟠 [Sentiment Analysis](text/api/sentiment_analysis.md) | 🟤 [Summarization](text/api/summarization.md)                      | 🟦 [Translation](text/api/translation.md)               |
| 🔵 [Classification](text/api/classification.md)         | 🔴 [Natural Language Inference](text/api/commonsense_reasoning.md) | 🟧 [Instruction Tuning](text/api/instruction_tuning.md) |
| 🟧 [Base Fine Tuner](text/api/base.md)                  |                                                                    |                                                         |

#### Bulk Inference

| 🌐 **Local & Huggingface**                               |                                                                     |                                                          |
| -------------------------------------------------------- | ------------------------------------------------------------------- | -------------------------------------------------------- |
| 🟢 [Language Model](text/bulk/language_model.md)         | 🟣 [Named Entity Recognition](text/bulk/ner.md)                     | 🟡 [Question Answering](text/bulk/question_answering.md) |
| 🟠 [Sentiment Analysis](text/bulk/sentiment_analysis.md) | 🟤 [Summarization](text/bulk/summarization.md)                      | 🟦 [Translation](text/bulk/translation.md)               |
| 🔵 [Classification](text/bulk/classification.md)         | 🔴 [Natural Language Inference](text/bulk/commonsense_reasoning.md) | 🟧 [Instruction Tuning](text/bulk/instruction_tuning.md) |
| 🟧 [Base Fine Tuner](text/bulk/base.md)                  |                                                                     |                                                          |

#### Fine-tuning

| 🌐 **Local & Huggingface**                                    |                                                                          |                                                               |
| ------------------------------------------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------- |
| 🟢 [Language Model](text/fine_tune/language_model.md)         | 🟣 [Named Entity Recognition](text/fine_tune/ner.md)                     | 🟡 [Question Answering](text/fine_tune/question_answering.md) |
| 🟠 [Sentiment Analysis](text/fine_tune/sentiment_analysis.md) | 🟤 [Summarization](text/fine_tune/summarization.md)                      | 🟦 [Translation](text/fine_tune/translation.md)               |
| 🔵 [Classification](text/fine_tune/classification.md)         | 🔴 [Natural Language Inference](text/fine_tune/commonsense_reasoning.md) | 🟧 [Instruction Tuning](text/fine_tune/instruction_tuning.md) |
| 🟧 [Base Fine Tuner](text/fine_tune/base.md)                  |                                                                          |                                                               |

| 🌐 **OpenAI**                                               |                                                                        |                                                             |
| ----------------------------------------------------------- | ---------------------------------------------------------------------- | ----------------------------------------------------------- |
| 🟢 [Classification](bolts/openai/classification.md)         | 🟣 [Natural Language Inference](bolts/openai/commonsense_reasoning.md) | 🟡 [Instruction Tuning](bolts/openai/instruction_tuning.md) |
| 🟠 [Language Model](bolts/openai/language_model.md)         | 🟤 [Named Entity Recognition](bolts/openai/ner.md)                     | 🟦 [Question Answering](bolts/openai/question_answering.md) |
| 🔵 [Sentiment Analysis](bolts/openai/sentiment_analysis.md) | 🔴 [Summarization](bolts/openai/summarization.md)                      | 🟧 [Translation](bolts/openai/translation.md)               |
| 🟧 [Base Fine Tuner](bolts/openai/base.md)                  |                                                                        |                                                             |

### ⚡ Data

#### Ingestion

| 🌐 **Streaming**                                   |                                        |                                        |                                              |
| -------------------------------------------------- | -------------------------------------- | -------------------------------------- | -------------------------------------------- |
| 🟢 [Http Polling](listeners/http_polling.md)       | 🟣 [Socket.io](listeners/socket.io.md) | 🟡 [gRPC](listeners/grpc.md)           | 🟠 [QUIC](listeners/quic.md)                 |
| 🟤 [UDP](listeners/udp.md)                         | 🔵 [Webhook](listeners/webhook.md)     | 🟥 [Websocket](listeners/websocket.md) | 🟩 [SNS](listeners/sns.md)                   |
| 🟧 [SQS](listeners/sqs.md)                         | 🟨 [AMQP](listeners/amqp.md)           | 🟫 [Kafka](listeners/kafka.md)         | 🟪 [Kinesis Streams](listeners/kinesis.md)   |
| 🟩 [MQTT](listeners/mqtt.md)                       | 🟨 [ActiveMQ](listeners/activemq.md)   | 🟫 [ZeroMQ](listeners/zeromq.md)       | 🟪 [Redis Pubsub](listeners/redis_pubsub.md) |
| 🟧 [Redis Streams](listeners/redis_streams.md{}{}) |                                        |                                        |                                              |

| 📦 **Databases**                           |                                                    |                                                |                                        |
| ------------------------------------------ | -------------------------------------------------- | ---------------------------------------------- | -------------------------------------- |
| 🟢 [HBase](databases/hbase.md)             | 🟣 [PostgreSQL](databases/postgres.md)             | 🔵 [MySQL](databases/mysql.md)                 | 🟠 [MongoDB](databases/mongodb.md)     |
| 🟢 [Cassandra](databases/cassandra.md)     | 🟣 [Redis](databases/redis.md)                     | 🔵 [Elasticsearch](databases/elasticsearch.md) | 🟠 [Oracle](databases/oracle.md)       |
| 🟢 [SQL Server](databases/sql_server.md)   | 🟣 [SQLite](databases/sqlite.md)                   | 🔵 [Neo4j](databases/neo4j.md)                 | 🟠 [Bigtable](databases/bigtable.md)   |
| 🟢 [DynamoDB](databases/dynamodb.md)       | 🟣 [Azure Table Storage](databases/azure_table.md) | 🔵 [Couchbase](databases/couchbase.md)         | 🟠 [InfluxDB](databases/influxdb.md)   |
| 🟢 [TimescaleDB](databases/timescaledb.md) | 🟣 [Teradata](databases/teradata.md)               | 🔵 [TiDB](databases/tidb.md)                   | 🟠 [Voltdb](databases/voltdb.md)       |
| 🟢 [Sybase](databases/sybase.md)           | 🟣 [DB2](databases/db2.md)                         | 🔵 [AWS Presto](databases/presto.md)           | 🟠 [Riak](databases/riak.md)           |
| 🟢 [MemSQL](databases/memsql.md)           | 🟣 [LDAP](databases/ldap.md)                       | 🔵 [AWS KeySpaces](databases/keyspaces.md)     | 🟠 [KairosDB](databases/kairosdb.md)   |
| 🟢 [Graphite](databases/graphite.md)       | 🟣 [Google FireStore](databases/firestore.md)      | 🔵 [AWS DocumentDB](databases/documentdb.md)   | 🟠 [Cockroach](databases/cockroach.md) |
| 🟢 [Cloud SQL](databases/cloud_sql.md)     | 🟣 [Azure CosmosDB](databases/cosmosdb.md)         | 🔵 [AWS Athena](databases/athena.md)           | 🟠 [ArangoDB](databases/arangodb.md)   |
| 🟢 [Nuodb](databases/nuodb.md)             | 🟣 [OpenTSDB](databases/opentsdb.md)               | 🔵 [Google Bigquery](databases/bigquery.md)    | 🟠 [Vertica](databases/vertica.md)     |
| 🟢 [Google Spanner](databases/spanner.md)  |                                                    |                                                |                                        |

#### Preprocessing

| 🌐 **Document Processing**                   | 🌐 **Image Processing**                                  | 🌐 **OCR**                                               |
| -------------------------------------------- | -------------------------------------------------------- | -------------------------------------------------------- |
| 🟣 [Parse PDF](ocr/ParsePdf.md)              | 🟡 [Predict image classes](ocr/ImageClassPredictor.md)   | 🔵 [TROCRImageOCR](ocr/TROCRImageOCR.md)                 |
| 🟣 [ParseCBZCBR](ocr/ParseCBZCBR.md)         | 🟡 [Train image classifier](ocr/TrainImageClassifier.md) | 🔵 [FineTuneTROCR](ocr/FineTuneTROCR.md)                 |
| 🟣 [ParseDjvu](ocr/ParseDjvu.md)             | 🟡 [Convert Images](ocr/ConvertImage.md)                 | 🔵 [TROCRImageOCRAPI](ocr/TROCRImageOCRAPI.md)           |
| 🟣 [ParseEpub](ocr/ParseEpub.md)             |                                                          | 🟢 [Pix2StructImageOCR](ocr/Pix2StructImageOCR.md)       |
| 🟣 [ParseMOBI](ocr/ParseMOBI.md)             |                                                          | 🟢 [Pix2StructImageOCRAPI](ocr/Pix2StructImageOCRAPI.md) |
| 🟣 [ParsePostScript](ocr/ParsePostScript.md) |                                                          | 🟢 [FineTunePix2Struct](ocr/FineTunePix2Struct.md)       |
| 🟣 [ParseXPS](ocr/ParseXPS.md)               |                                                          |                                                          |

### 📚 Library

| 📦 **cli**                            | 📦 **core**                       | 📦 **data**                                               | 📦 **core.state**                          |
| ------------------------------------- | --------------------------------- | --------------------------------------------------------- | ------------------------------------------ |
| 🟠 [geniusctl](core/cli_geniusctl.md) | 🟢 [bolt](core/core_bolt.md)      | 🟣 [input](core/core_data_input.md)                       | 🔴 [base](core/core_state_base.md)         |
| 🟠 [yamlctl](core/cli_yamlctl.md)     | 🟢 [spout](core/core_spout.md)    | 🟣 [output](core/core_data_output.md)                     | 🔴 [dynamo](core/core_state_dynamo.md)     |
| 🟠 [boltctl](core/cli_boltctl.md)     | 🟤 [base](core/core_task_base.md) | 🟣 [batch_input](core/core_data_batch_input.md)           | 🔴 [memory](core/core_state_memory.md)     |
| 🟠 [spoutctl](core/cli_spoutctl.md)   |                                   | 🟣 [batch_output](core/core_data_batch_output.md)         | 🔴 [postgres](core/core_state_postgres.md) |
| 🟠 [schema](core/cli_schema.md)       |                                   | 🟣 [streaming_input](core/core_data_streaming_input.md)   | 🔴 [redis](core/core_state_redis.md)       |
| 🟠 [discover](core/cli_discover.md)   |                                   | 🟣 [streaming_output](core/core_data_streaming_output.md) |                                            |
| 🟠 [docker](core/cli_dockerctl.md)    |                                   |                                                           |                                            |
|                                       |                                   |                                                           |                                            |
|                                       |                                   |                                                           |                                            |
