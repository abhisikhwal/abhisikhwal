Abhinav Sikhwal
ML Engineer & Applied Researcher · Berlin, Germany
MSc Data Science, AI & Digital Business
I develop computational methods that extract structured, interpretable knowledge from complex biological, legal, and cultural datasets — combining NLP, graph learning, and multi-modal machine learning to build systems that are both scientifically rigorous and practically deployable.

Research Interests

Biomedical AI & Computational Biology — disease mechanism discovery, multi-omics integration, survival analysis, interpretable ML for clinical translation
Knowledge Graph Construction — large-scale graph extraction from unstructured text, GNNs, biomedical ontologies
Natural Language Processing — RAG systems, document intelligence, information extraction from domain-specific corpora
Interpretable Machine Learning — SHAP-based feature attribution, cross-method validation, mechanistic discovery


Selected Projects
🧬 Multiple Myeloma Biomarker Discovery
Computational Biology · Machine Learning · Deep Learning
Integrative analysis of the MMRF CoMMpass dataset (859 patients, 30,018 genes) using seven independent computational methods — differential expression, pathway enrichment, GSEA, classical ML, deep learning, SHAP interpretability, and unsupervised clustering. All methods independently converged on MYC-driven cell cycle dysregulation and MTHFD2 metabolic reprogramming as hallmarks of Stage III progression.

6,356 significantly dysregulated genes (FDR < 0.05)
PyTorch classifier: 93.8% accuracy · 100% Stage III sensitivity (32/32)
GSEA: G2-M Checkpoint NES = 2.897, E2F Targets NES = 2.628 (FDR < 0.001)
Logistic Regression AUC = 0.874 · SHAP identifies MYC as top predictor across all models
4 molecular subtypes with distinct survival outcomes (1.55–2.95 years median)

→ github.com/abhisikhwal/myeloma-biomarker-project

🌿 Biomedical Knowledge Graph (In Progress)
Knowledge Graphs · Graph Neural Networks · Nutrigenomics
Constructing a large-scale biomedical knowledge graph (~60,000 nodes) that connects dietary compounds to gene-level biological mechanisms via curated pathway and interaction data. Combines NLP-based triple extraction with GNN-based link prediction to surface novel nutrient–gene–disease associations.

Graph construction from biomedical literature and curated databases
GNN-based reasoning over heterogeneous node/edge types
Target applications: precision nutrition, drug-nutrient interaction prediction


⚖️ Legal Document Intelligence — India Legal AI
RAG · Information Retrieval · NLP
End-to-end retrieval-augmented generation system for semantic search and structured Q&A over Indian legal acts and statutes (IPC, CrPC, Constitution, BNS, BNSS). Features intent classification, section-level chunking, and a FastAPI backend.

Sentence-BERT embeddings over 8 major Indian legal acts
Intent classification: punishment, definition, penalty range, offence scope
Reproducible pipeline: PDF extraction → enrichment → ChromaDB indexing → API

→ github.com/abhisikhwal/india-legal-ai

🕉️ Vedic Knowledge Graph (In Progress)
Knowledge Extraction · LLMs · Cultural AI
Structured extraction and graph representation of ancient Indian knowledge systems (Bhagavad Gita, Vedas, Ayurveda, Yoga, Astrology) using Llama 3.1 8B with domain-specific validation pipelines. Produces machine-readable triples across seven knowledge domains from Sanskrit-origin texts.

Technical Skills
AreaTools & FrameworksDeep LearningPyTorch, HuggingFace TransformersClassical MLScikit-learn, XGBoost, SHAPNLP & RetrievalSentence-BERT, spaCy, LangChain, ChromaDB, OllamaBioinformaticsgseapy, lifelines, DESeq2-equivalent (Python), UMAPGraph LearningNetworkX, PyG (PyTorch Geometric)Data & VizPandas, NumPy, SciPy, Matplotlib, SeabornBackend & InfraFastAPI, Docker, Git

Background
Before transitioning to AI/ML research, I co-founded and operated Nidra Niwas, a boutique heritage hotel in Jaipur, India — where I independently built ML-based demand forecasting, NLP-driven guest analytics, and an LLM-powered WhatsApp concierge system. This operational experience informs my approach to building AI systems that are not only technically rigorous but practically deployable in real-world constraints.

Currently

🔬 Completing biomedical knowledge graph pipeline (GNN + link prediction)
📖 Finalising Vedic knowledge extraction system across 7 domains
🎓 Applying to PhD programs in computational biology — with particular interest in multi-omics integration and knowledge-graph-driven mechanism discovery
💼 Open to industry roles in computational biology · life sciences · climate tech · NLP/LLM engineering
📍 Based in Berlin · Open to opportunities across Germany
