# Final_SGA_Spark_Advanced_LSML_1
Data: outbrain click prediction

Tasks: Using Spark RDD, DataFrame API and Python, calculate:

1. Top 10 most visited document_ids in the page_views_sample log

2. How many users have at least 2 different traffic_sources in the page_views_sample log (note the value is not a count, it's an encoded enum)

3. Top 10 most visited topic_ids in page_views_sample log (use documents_topics table)

The submission format is the result.json json file with top_10_documents, users and top_10_topics keys. For TOP-10 results, the answer must be written in the form of a sheet ordered from TOP-1 to TOP-10 with an id.

result.json example:

{
    "top_10_documents": [
        111,
        222,
        333,
        ...,
        1010
    ],
    "users": 10000,
    "top_10_topics": [
        11,
        22,
        33,
        ...,
        101
    ]
}
