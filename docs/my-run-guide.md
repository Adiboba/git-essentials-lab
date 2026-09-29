# Run guide

## Prerequisites

- JDK 17 or later
- Python 3.9 or later
- Git 2.23 or later

## Run the demo

    python3 run.py demo

On Windows, use py -3 run.py demo if that is how you run Python 3.

## What the demo does

The demo compiles the Java library application into a temporary directory and
runs a short scenario against it: adding books to the catalog, borrowing them
under the member limits, returning them, and printing loan receipts with any
overdue fees.