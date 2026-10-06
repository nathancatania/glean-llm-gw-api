# Glean LLM Gateway API Collection

A collection that can be loaded into Postman/Bruno etc to interface with the Glean LLM Gateway API endpoints.

> [!NOTE]
> This is a community repository. It is not endorsed, sponsored, managed, or supported by Glean. You use the contents at your own risk.

## Setup

1. Copy the URL of this repository: `https://github.com/nathancatania/glean-llm-gw-api`
    - Most apps can import a collection by GitHub URL.
    - Alternatively, you download the code or clone the repository for import.
2. Follow the instructions below to import the collection.

    - [Bruno - Import collections](https://docs.usebruno.com/get-started/import-export-data/import-collections)
    - [Postman - Import data into Postman](https://learning.postman.com/docs/getting-started/importing-and-exporting/importing-data#import-from-a-git-repository)

3. Populate the `INSTANCE_ID` and `GLEAN_API_KEY` variables in the `Default` environment.

    - The collection is set to automatically populate the base URL and Authorization header used for each API call when the above variables are populated.
    - For more info, see:
        - [Bruno - Environment variables](https://docs.usebruno.com/variables/environment-variables)
        - [Postman - Edit and set environment variables](https://learning.postman.com/latest-v-12/docs/use/send-requests/variables/environment-variables)