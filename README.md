# Backend Coding Challenge

## Requirements

Design a REST API that implements the following operations with binary trees:

Returns the height of a binary tree given an integers list
- `POST /v1/b-trees/height` 
    * input
    ```json
    {
       "toTree": [1,2,3,4,5,6,7,8]
    }
    ```
    * output
    ```json
        {
            "height": 3
        }
    ```
    
Returns the neighbor nodes of the node that contains the given integer
- `POST /v1/b-trees/neighbors` 
    * input
    ```json
    {
        "toTree":[1,2,3,4,5,6,7,8],
        "node: 2
    }
     
    ```
    * output
    ```json
        {
            "neighbors": [
                "left": null
                "right": 4
            ]
        }
    ```
    
Returns the BFS of the binary tree
- `POST /v1/b-trees/bfs` 
    * input
    ```json
    {
        "toTree":[-3,-2,-1,1,2,3,4,5,6,7,8],
    }
     
    ```
    * output
    ```json
        {
            "bfs": [x,y,z....]
        }
    ```

## Constraints

- You need to complete as much as you can in less than 50 minutes
- Use the programming language of your choice


## Advice

- **Try to design and implement your solution as you would do for real production code**. Show us how you create clean, maintainable code that does awesome stuff. Build something that we'd be happy to contribute to. This is not a programming contest where dirty hacks win the game.
- Documentation and maintainability are a plus, and don't you forget those unit tests.
- We don’t want to know if you can do exactly as asked (or everybody would have the same result). We want to know what **you** bring to the table when working on a project, what is your secret sauce. More features? Best solution? Thinking outside the box?

