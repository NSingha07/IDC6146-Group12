We present a novel generative language model for structured document retrieval, which is a key task in NLP. 
Our model treats a document as a tree of nodes, each corresponding to a document part (e.g., title, paragraph, section). 
We assign a language model to each node, which is either learned from the text (for leaf nodes) or interpolated from the child nodes (for inner nodes). 
This way, we capture the structure and context of the document. We use our model to rank documents and their parts based on structural queries, which specify the desired 
document part and its content. Our model offers a flexible and effective way to retrieve documents based on their structured content.

Data Scouce: 
The Alice in Wonderland dataset can be found at: \url{https://www.kaggle.com/datasets/chandan2495/alice-in-wonderland-gutenbergproject}

Nietzsche's bibliography dataset is available at: \url{https://www.kaggle.com/datasets/akouaorsot/nietzsches-bibliography}


