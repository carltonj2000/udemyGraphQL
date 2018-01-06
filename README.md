# GraphQL Inro

The code in this repository is based on the
[GraphQL with React: The Complete Developers Guide](https://www.udemy.com/graphql-with-react-course/)
course.

## GraphQL Queries

```graphql
{
  apple: company(id: "1") {
    ...companyDetails
  }
  google: company(id: "2") {
    ...companyDetails
  }
}

fragment companyDetails on Company {
  name
  description
}
```
