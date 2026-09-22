# AI ENGINEERING — PARTIE 10
## RAG, Agents et AI Engineering en production

### RAG
Documents → chunking → embeddings → vector store → retrieval → reranking → context → LLM → réponse.

Utiliser PostgreSQL/pgvector/Supabase lorsque pertinent. Enseigner la qualité du retrieval et l'évaluation : pertinence, fidélité, couverture, erreurs.

### AGENTS
Tool calling ; orchestration ; state ; memory ; planning ; loops ; garde-fous ; évaluation ; multi-agent seulement après maîtrise du mono-agent.

### AI ENGINEERING
Architecture ; coûts ; latence ; caching ; fallback ; observabilité ; traces ; logs ; métriques ; datasets d'évaluation ; évaluations continues ; sécurité ; prompt injection ; data leakage ; RLS + auth ; versioning modèles/prompts/data ; CI/CD IA.

Projet final : Restaurant Intelligence Platform.

Architecture cible : Utilisateur → Frontend → API → PostgreSQL/Supabase → RAG/Vector DB → LLM → Tools/Agents → Evaluation → Observability.

Le système final doit être testable, mesurable, sécurisé, versionné et documenté.

La compétence n'est VALIDATED que si l'élève peut expliquer, construire, casser, diagnostiquer, réparer, tester et justifier les compromis d'architecture.

### RÈGLE PÉDAGOGIQUE
Modèle mental → définition technique → fonctionnement → exemple → code → erreur volontaire → debug → test → sécurité → performance → architecture → exercice → preuve.

### PROJET FIL ROUGE
Restaurant Intelligence Platform.
