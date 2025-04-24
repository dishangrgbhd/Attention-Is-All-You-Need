# Attention-Is-All-You-Need
Read the paper "Attention Is All You Need" from Ashish Veshwani et al. I was so motivated and loved it so much that I decided to code the Transformer Architecture from scratch.
Unpacking the Transformer:

## 1. Encoder Block:

  -Multiple identical layers

  -Reading and Processing input sequence

  -Generate context-rich numerical representations

  -Uses self-attention and feed forward networks

## 2. Decoder Block:

  -Encoded input sequence -> output sequence

## 3. Positional Encoding:
   
  -Encode each token's position in the sequence
   
  -Order is crucial for modeling sequences

## 4. Attention Mechanisms:
  -Focus on important tokens and their relationships
   
  -Improve text generation

## 5. Self-attention:
  -Weighting token importance
   
  -Captures long-range dependencies

## 6. Multi-head attention:
  -Splits input into multiple heads
   
  -Heads capture distinct patterns, leading to richer representations

## 7. Position-wise feed-forward networks
  -Simple NNs that apply transformations
    
  -Each token is transformed independently

  -Position-independent
