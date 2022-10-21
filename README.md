# JPMC Task 3

## Task
- Update the grapth to track the ratio between two stocks over time and NOT the two stocks’ top_ask_price.

- Make this graph plot the upper and lower bounds and show when they get crossed

## Steps
- Changed the graph shema
- Added new attributes to the graph
- Modified the component lifecycle using componentDidUpdate

- The DataManipulator.ts file is responsible for processing the raw stock data we receive from the server
before the Graph component renders it.
- determines the structure of the object
returned by the generateRow to correspond to the return object must correspond to the schema
- update the generateRow function of the DataManipulator
class to properly process and aggregate raw server data
