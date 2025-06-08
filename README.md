# Testes com o Azure Language Studio

Um resumo do que aprendi testando a ferramenta de análise de texto da Azure.

## Análise de um texto sobre viagens

A ferramenta identificou:

### 📌 Palavras-chave principais
- "aeroporto"
- "atraso"
- "bagagem perdida"
- "hospedagem"
- "reclamação"
- "reembolso"
- "cliente insatisfeito"

### 😠 Análise de sentimentos
1. *"Meu voo atrasou 5 horas e perderam minha mala!"*  
   → **90% negativo**
2. *"O hotel não era como nas fotos e o atendimento foi péssimo."*  
   → **85% negativo**
3. *"Pelo menos o café da manhã era bom."*  
   → 60% negativo | 30% positivo
4. *"A empresa disse que vai reembolsar, mas ainda não vi nada."*  
   → **75% negativo**

### 🔍 Entidades reconhecidas
| Tipo | Exemplos |
|------|----------|
| Lugares | "aeroporto", "hotel" |
| Pessoas/Empresas | "cliente", "companhia aérea" |
| Problemas | "atraso", "bagagem perdida", "reembolso pendente" |

## Pra que serve isso?
- **Monitorar feedbacks** de clientes automaticamente
- **Identificar reclamações** urgentes (como bagagem perdida)
- **Extrair insights** de avaliações e reviews
- **Categorizar documentos** por tópicos


**Conclusão:** O Language Studio parece ser bem útil para analisar textos automaticamente, especialmente para atendimento ao cliente e análise de feedbacks!