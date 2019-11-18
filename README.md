# S3ContentsManager

A S3 ContentsManager implementation for Jupyter.

It aims to a be a transparent, drop-in replacement for Jupyter standard filesystem-backed storage system.
With this implementation of a Jupyter Contents Manager you can save all your notebooks, regular files, directories
structure directly to a S3/GCS bucket, this could be on AWS/GCP or a self hosted S3 API compatible like [minio](http://minio.io).
