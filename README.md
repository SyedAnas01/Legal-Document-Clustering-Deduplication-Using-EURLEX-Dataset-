# Legal Document Clustering & Deduplication (Using EURLEX Dataset)

This project demonstrates a simple pipeline for clustering legal documents using a real dataset from Hugging Face. It loads the EURLEX dataset (from LexGLUE), extracts the document text, generates semantic embeddings using a Sentence Transformer, reduces the dimensionality with UMAP, and clusters the documents with HDBSCAN.

## Features

- **Real Dataset:** Loads legal document texts from the EURLEX dataset via the Hugging Face Datasets library.
- **Embeddings:** Uses the pre-trained Sentence Transformer model `all-MiniLM-L6-v2` to generate document embeddings.
- **Dimensionality Reduction:** Applies UMAP to reduce high-dimensional embeddings to 2D for visualization.
- **Clustering:** Clusters documents using HDBSCAN.
- **Visualization:** Generates a scatter plot displaying the clusters.
- **CSV Output:** Saves the clustered data with cluster labels to a CSV file.

Future Enhancements
Use a larger subset or the entire dataset.

Experiment with different embedding models and clustering parameters.

Integrate deduplication logic for near-duplicate document detection.

Build a UI for interactive exploration of clusters.

License
This project is licensed under the MIT License.

Acknowledgements
Sentence Transformers for generating document embeddings.

UMAP for dimensionality reduction.

HDBSCAN for clustering.

Hugging Face Datasets for providing the legal dataset.

pandas and matplotlib for data manipulation and visualization.
