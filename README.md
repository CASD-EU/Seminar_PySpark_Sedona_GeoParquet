# Seminar_PySpark_Sedona_GeoParquet

In this seminar, we will show how to use **spark(pyspark)** and **sedona(spark)** to process geospatial big data.
We will also present [geoparquet](https://geoparquet.org/), a new geospatial data format.

https://sedona.apache.org/latest/

## Seminar outline

1. Data processing with `apache spark`
2. Spatial data processing with `apache sedona`
3. Working with GeoParquet


## 1. Data processing with apache spark

### 1.1. What is Apache Spark?

- Overview and use cases
- Spark architecture(e.g.driver, executors, cluster manager)
- Comparison with Hadoop MapReduce

### 1.2. How spark works?
- Lazy evaluation
- Actions vs. Transformations

### 1.3. Getting Started with PySpark

- Installing Spark (standalone mode)
- Basic SparkSession setup
- First spark application

### 1.4: Wangling data with PySpark

- Reading CSV, Parquet
- Cleaning data(e.g. handling missing values, trimming and normalizing strings, removing duplicates)
- Data Aggregation and Joins
- User-defined functions (UDFs)
- writing data in parquet(partitioning and performance tuning basics)

## 2. Spatial data processing with apache sedona

### 2.1 What is Apache Sedona?

- Overview and use cases
- Sedona architecture and integration with Spark

### 2.2: Getting Started with Sedona(pyspark)

- Installing Sedona with JAR packages
- Registering Sedona functions and types

### 2.3: Wangling geospatial data with Sedona

- Reading geospatial data(e.g. )
- Creating geometry column by using `ST_Point, ST_GeomFromWKT, ST_GeomFromText, etc.`
- Use spatial predicates (e.g. `ST_Contains, ST_Within, ST_Intersects`)
- Use spatial joins and indexing(e.g. Spatial join with bounding boxes and geometries, building and using spatial indexes (`R-Tree, Quad-Tree`))
- Spatial Aggregation and Distance(e.g. calculating distances with `ST_Distance`, aggregating geometries by group (e.g., ST_Envelope_Aggr)) 

## 3. Working with GeoParquet

### 3.1 Introduction to parquet

### 3.2 Introduction to GeoParquet
- What is GeoParquet?
- Advantages over `Shapefile, GeoJSON, CSV+WKT`
- GeoParquet spec overview: geometry_columns, crs, encoding, bbox, orientation
- Reading and Inspecting GeoParquet
- Writing Spatial Data with geoparquet with CRS awareness


