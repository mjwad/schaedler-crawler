# Python Playwright Template

This project provides a template for building Apify Actors using Python with Playwright. It includes useful tools like request queues, datasets, and input schema validation, making it ideal for scraping web pages or automating tasks with headless browsers.

## Features

- **[Apify SDK](https://docs.apify.com/sdk/python/)**: A comprehensive toolkit for building [Actors](https://apify.com/actors) and scrapers in Python.
- **[Input Schema](https://docs.apify.com/platform/actors/development/input-schema)**: Define and easily validate a schema for your Actor's input.
- **[Request Queue](https://docs.apify.com/sdk/python/docs/concepts/storages#working-with-request-queues)**: A queue where URLs to be scraped can be stored and processed.
- **[Dataset](https://docs.apify.com/sdk/python/docs/concepts/storages#working-with-datasets)**: Store structured data with attributes that remain consistent across records.
- **[Playwright](https://pypi.org/project/playwright/)**: A browser automation library that supports scraping modern web applications.

## Resources

Here are some useful resources to help you get started:

- [Playwright for Web Scraping in 2023](https://blog.apify.com/how-to-scrape-the-web-with-playwright-ece1ced75f73/)
- [Scraping Single-Page Applications with Playwright](https://blog.apify.com/scraping-single-page-applications-with-playwright/)
- [How to Scale Puppeteer and Playwright](https://blog.apify.com/how-to-scale-puppeteer-and-playwright/)
- [Apify Integrations](https://apify.com/integrations): Integrate Apify with services like Zapier, Make, GitHub, Google Drive, and more.
- [Video Guide: Using Apify API](https://www.youtube.com/watch?v=ViYYDHSBAKM)
- [Building a Web Scraper: Video Guide](https://www.youtube.com/watch?v=u-i-Korzf8w)

## Getting Started

To develop and run an Actor locally, follow the guide on building an Actor locally [here](https://docs.apify.com/platform/actors/development#build-actor-locally).

Once you’ve installed the necessary dependencies, run the Actor locally using this command:

```bash
apify run
```

## Deploy to Apify

### Connect Git repository to Apify

If you've created a Git repository for the project, you can easily connect to Apify:

1. Go to [Actor creation page](https://console.apify.com/actors/new)
2. Click on **Link Git Repository** button

### Push project on your local machine to Apify

You can also deploy the project on your local machine to Apify without the need for the Git repository.

1. Log in to Apify. You will need to provide your [Apify API Token](https://console.apify.com/account/integrations) to complete this action.

    ```bash
    apify login
    ```

2. Deploy your Actor. This command will deploy and build the Actor on the Apify Platform. You can find your newly created Actor under [Actors -> My Actors](https://console.apify.com/actors?tab=my).

    ```bash
    apify push
    ```

## Documentation reference

To learn more about Apify and Actors, take a look at the following resources:

- [Apify SDK for JavaScript documentation](https://docs.apify.com/sdk/js)
- [Apify SDK for Python documentation](https://docs.apify.com/sdk/python)
- [Apify Platform documentation](https://docs.apify.com/platform)
- [Join our developer community on Discord](https://discord.com/invite/jyEM2PRvMU)
