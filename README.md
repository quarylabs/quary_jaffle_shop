## Example Quary project w/ DuckDB: `jaffle_shop`

`jaffle_shop` is a fictional ecommerce store. This Quary project transforms raw data from DuckDB into a customers and orders model ready for analytics.

![template_duck_db](https://github.com/quarylabs/quary_jaffle_shop/assets/132601011/369d6f9f-2be3-4fdd-bcb6-58f9691a3009)

This repo is a self-contained playground Quary project, useful for trying Quary, and communicating some of the core Quary concepts.

### What's in this repo?
This repo contains .csv data that includes some (fake) raw data from a fictional app.
The raw data consists of customers, orders, and payments, with the following entity-relationship diagram:

### Opening this project
The beauty of Quary is that it's easy to start interacting with this project.

You can do this by clicking the period key `.` on your keyboard straight from this repository. It will take you to an in-browser version of vscode.

Once there, you can install the extension by either:

- Clicking the `Install` button in the bottom right corner, when VS Code asks you to install recommended extensions
- Clicking on the extensions icon and installing the extensions from there in the `Recommended` tab

To get a feel of interacting with data models, head to `customers.sql` and hit the `CMD+D` (ctrl on windows) shortcut to open the model documentation or `CMD+enter` (ctrl on windows) shortcut to see the transformed data.

---
For more information on Quary:
- Star our [opens-source repo](https://www.github.com/quarylabs/quary).
- Read the [Quary documentation](https://www.quary.dev/docs).
- Join the [Quary community](https://join.slack.com/t/quarylabs/shared_invite/zt-2dlbfnztw-dMLXJVL38NcbhqRuM5gUcw).
---

### What is a jaffle?
A jaffle is a toasted sandwich with crimped, sealed edges. Invented in Bondi in 1949, the humble jaffle is an Australian classic. The sealed edges allow jaffle-eaters to enjoy liquid fillings inside the sandwich, which reach temperatures close to the core of the earth during cooking.

# Attribution notice
This template example project is copied and modified for Quary based upon DBT (Data Build Tool)'s project example. [DBT/jaffle_shop](https://github.com/dbt-labs/jaffle_shop/tree/main) is licensed under the Apache License 2.0.

