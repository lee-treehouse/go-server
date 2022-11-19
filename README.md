# go-server
go server inspired by free code camp 11 in 1 golang tute https://www.youtube.com/watch?v=jFfo23yIWac

## instructions for running locally 

```
 go build -buildvcs=false
 go run main.go
```



next steps - create the flowchart from the tutorial in mermaid.js and embed in this readme

```mermaid
%%{init: {'theme': 'neutral' } }%%
graph TD
    A[Server] --> B["/"]
    A --> C["/hello"]
    A --> D["/form"]
B --> E[index.html]
C --> F[hello func]
D --> G[form.html]     
```