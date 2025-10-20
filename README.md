# Learn Credyt

This repository contains various resources for learning how to use Credyt.

## Bruno Collections

[Bruno](https://www.usebruno.com/) is an open-source API client that integrates nicely with Git - kind of like Postman, but better 🙂

We've provided various bruno collections in the `./bruno` directory to accompany [our docs](https://docs.credyt.ai).

After [downloading Bruno](https://www.usebruno.com/downloads):

1. Clone this repository

   ```
   git clone git@github.com:credyt/learn.git ./learn-credyt
   ```

2. Open the Bruno app and select "Open Collection"
3. Choose the collection directory `./learn-credyt/bruno/credyt-api`
4. In the top right of the Bruno app select the environments dropdown and select "Configure"
5. Obtain your API keys from the [Credyt Portal](https://app.credyt.ai) and add them under the `credytApiKey` variable for your desired environment (`test` or `live`). Make sure to "Save" the changes.
6. Select the target environment in Bruno

You should now be all set to make requests to the Credyt API and follow along with the docs.
