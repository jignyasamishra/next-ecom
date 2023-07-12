
# Next-ecom
An ecoomerce website using Next.js and TailwindCss.


## Documentation

[Documentation](https://linktodocumentation)


## Deployment

To deploy this project run

```bash
  >cd my-app
  >npm i
  >npm run dev
```


## API Reference

#### Get all items

```http
https://fakestoreapi.com/products
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

