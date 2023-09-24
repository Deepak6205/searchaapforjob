
#  url-hit-counter

Build job search portal using Spring Boot and H2 Database




 


## 🚀 About Me
I'm a full stack developer...

https://github.com/Deepakkr3

deepakbaitha7905@gmail.com
## API Reference

#### GetMapping

```http
 @GetMapping("jobs/jobType/{jobType}")
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. to get job by job type |

#### Get item 

```http
@GetMapping("job/salary/{salary}")
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. to get job by job salary  |

```http
@GetMapping("jobs/description/location")
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. to get job by job location  |

