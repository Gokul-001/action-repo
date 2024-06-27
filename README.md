# Dev Assessment - Webhook Receiver

Please use this repository for constructing the Flask webhook receiver.
s
*******************s
vfgd
## Setupvsswf
virtualenv venvq
```sssss
* Activate the virtual envsw
ss
```bash
source venv/bin/activates
```s

* Install requirementsdqwdqdqs
w
```bashw
pip install -r requirements.txt
```w

* Run the flask application (In production, please use Gunicorn)

```bash
python run.py
```

* The endpoint is at:

```bash
POST http://127.0.0.1:5000/webhook/receiver
```

You need to use this as the base and setup the flask app. Integrate this with MongoDB (commented at `app/extensions.py`)

*******************
