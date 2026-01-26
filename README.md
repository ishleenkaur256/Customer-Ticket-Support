# Customer-Ticket-Support
*Context Awareness*: Simple string matching fails on context (e.g., matching "Windows" when someone is talking about "house windows" vs "OS Windows"). NER looks at token neighbors.
</br>*Pattern Robustness*: My engine uses Regex for Error Codes (like 0x8004...), which string matching cannot do effectively.
</br>*Scalability*: Adding a new product only requires adding one pattern to the EntityRuler rather than writing 50 new if/else statements.
