# Claude 3.5
## Use Case

This lets us generate notes for literature notes. 
Add the model output as a Zotero note related to the item then run `Zotero Integration: Create Literature Note`.

### Summary Prompt

```
Summarize this paper in a few sentences. Use bullet points for each key topic, citing evidence with page numbers in the paper. Preface your response with the Text “#Summary/Claude3_5Sonnet”
```

### Hypothesis Prompt

```
What is the key hypothesis for this paper? Use page numbers from the paper to cite each statement . Preface your answer with the text “#Hypothesis/Claude3_5Sonnet”.
```

### Methodology Prompt

```
What is the methodology used in this paper? Focus on the methods and not on the authors. Please be specific about the methods used. Use page numbers in the paper to cite each statement. Preface your text with the word “#Methodology/Claude3_5Sonnet”
```

### Result Prompt

```
What is the key Result of this paper? Use page numbers from the paper to cite each statement . Preface your answer with the word “#Results/Claude3_5Sonnet”
```

### Significance Prompt

```
What is the significance of this work as it relates to X? Focus on novelty. Use page numbers from the paper to cite each statement . Preface your answer with the text “#Significance/Claude3_5Sonnet”
```