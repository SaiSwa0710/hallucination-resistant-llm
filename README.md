# hallucination-resistant-llm

Retrieval-Augmented Generation (RAG) pipeline built on top of GPT to reduce hallucinations by grounding responses in curated context from Avengers: Endgame. Returns accurate answers when context exists, otherwise responds with "I don't know". Includes accuracy evaluation for correct vs. incorrect answers.



\# Hallucination-Resistant LLM with RAG



This project implements a Retrieval-Augmented Generation (RAG) pipeline on top of a GPT-based LLM to minimize hallucinations. The model is provided with curated context from the movie \*Avengers: Endgame\* and is designed to:



\- Return definitive, fact-based answers to questions \*\*only if\*\* relevant context exists.

\- Reply with `"I don't know"` when the answer is outside the provided context.

\- Track and score the number of correct vs. incorrect responses.



\## Features

\- \*\*RAG pipeline\*\* for context retrieval.

\- \*\*Hallucination control\*\* by restricting model responses to provided data.

\- \*\*Accuracy evaluation\*\* with correct/incorrect scoring.

\- \*\*Movie-specific QA\*\* using \*Avengers: Endgame\* as the knowledge base.



\## Tech Stack

\- GPT-based LLM

\- Retrieval-Augmented Generation (RAG)

\- Custom evaluation metrics



\## Example

\*\*Q:\*\* Who sacrificed themselves to get the Soul Stone?  

\*\*A:\*\* Black Widow.  



\*\*Q:\*\* Who won the 1998 FIFA World Cup?  

\*\*A:\*\* I don't know.  



\## License

MIT License



