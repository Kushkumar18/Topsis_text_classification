# Topsis_text_classification
This will calculate the TOPSIS scores, rank the models, and display a bar chart of the rankings.

## Output
The output will include a table with the following columns:
- **Model**: Name of the model.
- **Accuracy**: Accuracy of the model.
- **F1-score**: F1-score of the model.
- **Inference Time (ms)**: Inference time of the model.
- **Model Size (MB)**: Size of the model.
- **TOPSIS Score**: The calculated TOPSIS score.
- **Rank**: The rank based on the TOPSIS score.

A bar chart will also be displayed showing the TOPSIS scores for each model.

## Example Output

| Model      | Accuracy | F1-score | Inference Time (ms) | Model Size (MB) | TOPSIS Score | Rank |
|------------|----------|----------|---------------------|-----------------|--------------|------|
| RoBERTa    | 0.92     | 0.93     | 15                  | 510             | 0.735        | 1    |
| XLNet      | 0.91     | 0.92     | 19                  | 710             | 0.715        | 2    |
| BERT       | 0.90     | 0.89     | 11                  | 430             | 0.690        | 3    |
| DistilBERT | 0.86     | 0.85     | 7                   | 240             | 0.565        | 4    |
| ALBERT     | 0.88     | 0.87     | 9                   | 190             | 0.590        | 5    |

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
**Kush Kumar**  
Roll No: 102203622  
Email: kkumar1_be22@thapar.edu
