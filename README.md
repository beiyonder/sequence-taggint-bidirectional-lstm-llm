## Theoretical Approach

### Data Preprocessing
- Feature normalization using Z-score transformation
- Formula: `z = (x - μ) / σ`
- Standardizes input features to zero mean and unit variance

### Embedding Strategy
- Utilized Universal Sentence Encoder
- Semantic similarity measured by cosine similarity
- Formula: `cos(θ) = (a · b) / (|a| * |b|)`

### Model Architecture
- Bi-directional LSTM with attention mechanism
- Loss function: Cross-entropy
- Formula: `L = -Σ(y_t * log(ŷ_t))`

### Performance Metrics
- F1 Score: 0.97
- Regularization: L2 weight decay