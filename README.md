| Updating Modules | CNN (Ours) | LSTM (Ours) | Transformer (Ours) | GPT-2   |
|-------------------|-------------|--------------|---------------------|---------|
| Classifiers       | 50K | 205K | 2K  | 800K |
| Word embedding    | N/A | N/A | 120K | 39M |
| Feature extractor | 6K | 17K | 88K | 84M |
| Full Model        | 56K | 222K | 210K | 124M |


| Lambda Range | No update | T   | TC  | TWC | TFC | TWFC |
|--------------|-----------|-----|-----|-----|-----|------|
| 0.1~0.5      | 20        | 80  | 0   | 0   | 0   | 0    |
| 0.6          | 0         | 20  | 0   | 0   | 40  | 40   |
| 0.7~0.9      | 0         | 0   | 0   | 0   | 40  | 60   |

