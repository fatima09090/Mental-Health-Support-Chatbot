# Mental-Health-Support-Chatbot


## Project Summary
This project fine-tunes **DistilGPT-2** on a small, custom dataset of mental health–focused conversations to create an empathetic AI chatbot. The model is designed to generate supportive, emotionally aware responses while maintaining appropriate boundaries and avoiding clinical claims.

## Results & Performance
- **Dataset**: conversation pairs  
- **Training Configuration**:  
  - 10 epochs  
  - Loss reduced from **2.20 → 0.35**
- **Final Validation Loss**: **0.32**
- **Response Quality**: Mixed  
  - Some coherent and empathetic responses  
  - Some hallucinated or off-topic outputs

## Key Findings

### Model Successfully Learned
- Empathetic tone and supportive language
- Domain-specific terminology (e.g., anxiety, depression, coping strategies)
- Basic conversational flow and structure

### Issues Identified
- **Hallucination**: Occasional generation of unrelated content (e.g., animals, mythology, geography)
- **Incoherence**: Responses sometimes merge multiple training examples unnaturally
- **Length Control**: Tendency toward verbose and rambling outputs

## Technical Specifications
- **Base Model**: DistilGPT-2 (82M parameters)
- **Sequence Length**: 256 tokens
- **Training Objective**: Causal language modeling (next-token prediction)

## Sample Outputs

### Coherent Responses
- “Sleep issues are common with stress. Try establishing a consistent bedtime routine…”
- “When things feel hopeless, it’s important to remember that feelings are temporary…”

### Hallucinated Responses
- Mentions of unrelated topics (e.g., animals, random facts, locations)
- Nonsensical or impractical coping strategies


