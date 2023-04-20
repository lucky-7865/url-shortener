
# URL Shortener

A powerful URL shortener application built with Golang, utilizing Redis as its high-performance database. With built-in rate limiter functionality, this application ensures efficient and secure URL shortening, making it ideal for managing links in high-traffic environments. Experience fast performance and robust rate limiting capabilities with this cutting-edge URL shortener solution.
  

![URL architecture](https://user-images.githubusercontent.com/87746680/233459714-e9d3722a-e349-45d3-a27f-f617ce2d64f1.PNG)


## Run Locally
Clone the project

```bash
  git clone https://github.com/lucky-7865/url-shortener.git
```

Go to the project directory

```bash
  cd url-shortener
```

Install dependencies

```bash
  go mod download
```

Start the server

```bash
  docker-compose up 
```

The server will get Start on localhost:3000. You can use any API platform like POSTMAN to interact with the application and shorten the URLs

![url-shortener](https://user-images.githubusercontent.com/87746680/233461582-44ebd49e-d2f6-4867-98e2-849f4e5576fa.PNG)

As you can see we shorten up a big URL. Instead of long and complex URL we can use this short URL, which will reduce the storage and bandwith as it has fewer characters. Thus it is more efficient and use less resources over the network.

The rate limiting feature is designed to manage the incoming requests to prevent abuse and protect the system resources and ensure optimal performance and reliability.

