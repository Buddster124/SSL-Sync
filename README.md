# SSL-Sync
This is a tool designed for syncing SSL certs from on machine to another. 



usage: main.py [-h] [-s] [-v] [--ignore-existing] [--sync-time SYNC_TIME] [--source-ip SOURCE_IP] [--source-cert-name SOURCE_CERT_NAME] [--output-dir OUTPUT_DIR] [--output-cert-name OUTPUT_CERT_NAME]

optional arguments:
  -h, --help            show this help message and exit
  -s, --server          Start the program in server mode (default: False)
  -v, --verbose         increase verbosity (default: False)
  --ignore-existing     skip files that exist (default: False)
  --sync-time SYNC_TIME
                        Sync file every x(Days) (default: None)
  --source-ip SOURCE_IP
                        IP of the SSL sync server - Not Needed If Server (default: None)
  --source-cert-name SOURCE_CERT_NAME
                        Name of cert to pull from server (default: None)
  --output-dir OUTPUT_DIR
                        Destination location For SSL Certs (default: None)
  --output-cert-name OUTPUT_CERT_NAME
                        Name For The SSL Certs (default: None)
