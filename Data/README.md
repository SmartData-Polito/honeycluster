# Data

This folder contains the Cowrie data used for the paper [Towards NLP-based Processing of Honeypot Logs](https://ieeexplore.ieee.org/document/9799396).

The data were collected on multiple Cowrie instances, deployed at 24 distinct IP addresses of a university campus network for 8 months.


## Howto

The data were split into smaller chunks of 10MB in order to be uploaded on GitHub. To obtain the original file back, run:

```bash
cat cowrie_data_part_* > cowrie_data.csv
```

