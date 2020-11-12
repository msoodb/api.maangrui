# api.maangrui

## Want to use this project?

1. Sign up for [Stripe](https://stripe.com/) (if you don't already have an account).

1. Set the Stripe Secret [key](https://stripe.com/docs/keys) as an environment variable:

    ```sh
    $ export STRIPE_SECRET_KEY=UPDATE_ME
    ```



1. Run the server-side Flask app in one terminal window:

    ```sh
    $ python3 -m venv env
    $ source env/bin/activate
    (env)$ pip install -r requirements.txt
    (env)$ python app.py
    ```

    Navigate to [http://localhost:5000](http://localhost:5000)
