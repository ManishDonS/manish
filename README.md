# This command is to install autoback dependency.
.cd /opt/odoo-17.0/
. ./venv/bin/activate
pip install dropbox
sudo systemctl restart odoo
