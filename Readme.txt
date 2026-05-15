#video
https://www.youtube.com/watch?v=KSwPR9eig7w&t=23s

#Code
https://github.com/milind1248/semantic-search-elastic-search-and-BERT-vector-embedding

#Elastic search download - 
https://www.elastic.co/downloads/elasticsearch (for window zip file)

#Run elastic search locally-
C:\Users\Lenovo\Downloads\elasticsearch-9.4.1-windows-x86_64\elasticsearch-9.4.1\bin\elasticsearch.bat

# in Browser
https://localhost:9200/
Username: elastic
Password: AUHVn9oi7sAmpO6vM_zB

Display on browser
{
  "name" : "DESKTOP-K1HPRJM",
  "cluster_name" : "elasticsearch",
  "cluster_uuid" : "rXGPLVryStaHzX_VQHvXaQ",
  "version" : {
    "number" : "9.4.1",
    "build_flavor" : "default",
    "build_type" : "zip",
    "build_hash" : "3c7c6027c5769d860d87448e2749f4c550a239da",
    "build_date" : "2026-05-08T10:08:29.383338563Z",
    "build_snapshot" : false,
    "lucene_version" : "10.4.0",
    "minimum_wire_compatibility_version" : "8.19.0",
    "minimum_index_compatibility_version" : "8.0.0"
  },
  "tagline" : "You Know, for Search"
}

#Pip install required
pip install Elasticsearch
pip install pandas
pip install -U sentence-transformers
pip install streamlit
pip install torchvision

#run streamlit
streamlit run searchApp.py
