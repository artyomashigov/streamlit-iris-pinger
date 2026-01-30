# streamlit-iris-pinger

Pings the [Iris Predictor app](https://iris-model-aa.streamlit.app/) on a schedule so it doesn’t go inactive. Streamlit Community apps are free but go to sleep after 12–24 hours without traffic, and this repository uses GitHub Actions to periodically hit the site and keep it warm.
