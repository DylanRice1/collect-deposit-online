# Collect deposits online quickly

- Display items available for booking
- Ask for time/date
- Setup payment for later (authorise payment so can collect once service confirmed)


## Setup

```
python3 -m venv venv
. venv/bin/activate
pip install -r requirements.txt
cp ./app/.env.example ./app/.env  # update with your stripe key (You must sign up for a stripe developer account [https://dashboard.stripe.com/register] in order to get the stripe API ID
```

## Run

```
. venv/bin/activate
export FLASK_DEBUG=1
python app.wsgi
```

http://127.0.0.1:5500/
