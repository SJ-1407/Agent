# Agent Implementation

## Summary Node in the Graph

In the first cell of code, I implemented a node in the graph dedicated to summarization without using any database. The agent's workflow allowed states to be updated iteratively, enabling the summarizer to consolidate insights gathered during the process.

## Chroma Database Integration

In the second cell of code, I integrated Chroma database as specified in the task requirements. The Chroma database was utilized to store and retrieve data based on similarity searches. This integration facilitated the retrieval of relevant information for summarization directly from the database .

### Running the Outputs

You can run both outputs to compare the effectiveness and efficiency of summarization:

1. **Summary Node Output**: Execute the first cell to observe how the agent summarizes insights without using a database.

2. **Chroma Database Output**: Execute the second cell to witness the agent's ability to summarize data retrieved from the Chroma database using similarity search.

