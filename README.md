# Barcode Partitioning
## Introduction
BarcodePartitioning is a Python package for determining barcodes from FASTQ files. It is written to accept many different formats of barcodes and uses parallelization (DASK)

## Dependencies

## Basic Usage
```
usage: Barcodes.py [-h] -f FORWARD FASTQ [-r REVERSE FASTQ] -s SAMPLE SHEET -b
                   BARCODES [-e ERROR RATE]

optional arguments:
  -h, --help            show this help message and exit
  -f FORWARD FASTQ, --forward-fastq FORWARD FASTQ
                        Provide the forward or single-end FASTQ file
  -r REVERSE FASTQ, --reverse-fastq REVERSE FASTQ
                        Provide the reverse FASTQ file [optional]
  -s SAMPLE SHEET, --sample-sheet SAMPLE SHEET
                        Sample table
  -b BARCODES, --barcodes BARCODES
                        Barcodes CSV file
  -e ERROR RATE, --error-rate ERROR RATE
                        Barcodes error rate, defaults to '2'
```
