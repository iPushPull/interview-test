# Interview Test

Create an app with two views. You can use any JavaScript framework of your choice.

## View One

Load and display a list of domains and underneath each domain a list of pages.

You should be able to click on any page item that will navigate to **View Two**.

Use our API end-point below to get a list of domains and pages.

```
https://www.ipushpull.com/api/1.0/domain_page_access/
```

## View Two

Load and display page content. 

The API end-point below contains a multi-dimensional array of data that represents a page.

Iterate over this array and display each **value**.

There should also be a button to reload the page content.

```
https://www.ipushpull.com/api/1.0/domains/id/[DOMAIN_ID]/page_content/id/[PAGE_ID/
// Example output
{
    ...
    "id": "123",
    "name: "Example",
    ...
    "content": [
        [
            {
                "value": "Example",
                ...
            }
        ]
        ...
    ]
}

```

## Code

You can provide a link to your solution via a service such as https://codesandbox.io/ or upload it to a host such as https://github.com/
