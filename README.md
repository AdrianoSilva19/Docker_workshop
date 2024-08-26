# docker_workshop

Steps to be done:

### First container

- Create Generic Code to be used, a simple ETL, receives a file, transforms the data and saves it in another file(json maybe):

  - Must acept a file
  - Utilize that file and output another file

- Create image with that code:
  - Able to pass the file to the code inside
  - Utilize the data in the file to grnerate a series of graphs

### Second container

- Create generic code that reads a json and outputs a graph
  - must read the json saved by the last container
  - create a graph with it and save it in another folder as a png

Docker-compose with both containers.
Each of us should have

This should encompass some things such as volumes and iteractions between containers, in the next steps new infos will be given such a how to put diferent containers comunicating with each other throughout ports.
