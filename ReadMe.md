python3 -m venv env
source env/bin/activate
pip3 install openmetadata-ingestion[docker]
metadata docker --start
# http://localhost:8080  admin/admin

# view metadata http://localhost:8585

