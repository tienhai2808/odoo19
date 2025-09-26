# Odoo19

## Getting started with Odoo19

Clone repo
```bash
git clone https://github.com/tienhai2808/odoo19.git
```

Install relevant libraries, requires [Python 3.12+](https://www.python.org/search/?q=3.12)
```bash
python -m venv myenv
```
```bash
source myenv/bin/activate
```
```bash
pip install -r requirements.txt
```

Create an odoo.conf file based on the sample debian/odoo.conf file

Requires PostgreSQL application [click here to download](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads)
PostgreSQL will run on the port you configure, remember the port, username and password then use it in the odoo.conf file

Run application
```bash
python odoo-bin -c "odoo.conf"
```

### Good Luck🍀😚
