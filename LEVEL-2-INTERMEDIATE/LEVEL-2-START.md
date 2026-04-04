# 🚀 LEVEL 2: INTERMEDIATE - Getting Started

**Estimated Duration**: 49-60 hours | **Modules**: 4 | **Notebooks**: 15+  
**Prerequisites**: Complete [LEVEL-1-BEGINNER](../LEVEL-1-BEGINNER/LEVEL-1-START.md) ✅  

---

## 📊 What You'll Learn at Level 2

You've mastered Python basics and fundamental ML concepts. Now it's time to go **deeper and broader**:

**Core Skills**:
- 📐 Advanced mathematics for ML (Linear Algebra, Calculus, Statistics)
- 📊 Data science workflows and analysis
- 🤖 Production ML libraries (scikit-learn, pandas, NumPy)
- 🧠 **Introduction to LLMs and Transformer architecture**
- ⚙️ **LLM Models Overview** - GPT, Claude, Llama, Gemini
- 🎯 **Prompt Engineering** for effective LLM usage
- 🔗 **Basic LangChain** patterns and chains

---

## 📚 Module Breakdown

### Module 4: Mathematics for ML (10-12 hours)
**Goal**: Strong mathematical foundation for ML algorithms  
**Key Topics**:
- Linear algebra (matrices, eigenvalues, decomposition)
- Calculus (gradients, optimization)
- Probability and statistics
- Information theory

**Learning Outcomes**:
✅ Understand backpropagation math  
✅ Implement optimization algorithms  
✅ Analyze statistical properties of data  

**Path**: [04-mathematics-for-ml/README.md](./04-mathematics-for-ml/README.md)

---

### Module 5: Data Science & Analysis (12-14 hours)
**Goal**: Professional data analysis and visualization  
**Key Topics**:
- Exploratory data analysis (EDA)
- Data cleaning and preprocessing
- Statistical analysis
- Data visualization best practices
- Working with SQL and databases

**Learning Outcomes**:
✅ Perform thorough data exploration  
✅ Handle missing data professionally  
✅ Create publication-quality visualizations  
✅ Query databases efficiently  

**Path**: [05-data-science-analysis/README.md](./05-data-science-analysis/README.md)

---

### Module 6: ML Libraries & Tools (12-14 hours)
**Goal**: Master scikit-learn and production ML tools  
**Key Topics**:
- scikit-learn ecosystem
- Feature engineering
- Model selection and hyperparameter tuning
- Cross-validation
- Pipelines and preprocessing

**Learning Outcomes**:
✅ Build ML pipelines  
✅ Tune models systematically  
✅ Evaluate models properly  
✅ Handle production data  

**Path**: [06-ml-libraries/README.md](./06-ml-libraries/README.md)

---

### Module 7: LLM Fundamentals & Models (15-18 hours) ⭐ NEW
**Goal**: Understand and use Large Language Models effectively  
**Key Topics**:
- Transformer architecture deep dive
- LLM model families (OpenAI, Google, Meta, Anthropic)
- Model capabilities and limitations
- Prompt engineering techniques
- Basic API usage and integration
- LangChain fundamentals

**Learning Outcomes**:
✅ Choose the right LLM for tasks  
✅ Engineer effective prompts  
✅ Integrate LLMs into applications  
✅ Understand model trade-offs  
✅ Build with LangChain  

**Path**: [07-llm-basics/README.md](./07-llm-basics/README.md)

**Notebooks in this module**:
1. [01-transformer-architecture.ipynb](./07-llm-basics/01-transformer-architecture.ipynb) - **3-4 hours**
   - Attention mechanism
   - Transformer layers
   - Positional encoding
   - Multi-head attention

2. [02-llm-models-overview.ipynb](./07-llm-basics/02-llm-models-overview.ipynb) - **3-4 hours**
   - GPT family (GPT-4, GPT-3.5)
   - Claude (Anthropic)
   - Llama 2 (Meta)
   - Gemini (Google)
   - Open-source models
   - Model comparison and selection

3. [03-prompt-engineering.ipynb](./07-llm-basics/03-prompt-engineering.ipynb) - **2-3 hours**
   - Prompt structure
   - Few-shot learning
   - Chain-of-thought prompting
   - Role-playing and system prompts
   - Prompt optimization

4. [04-embedding-models.ipynb](./07-llm-basics/04-embedding-models.ipynb) - **2-3 hours**
   - Text embeddings
   - Semantic search
   - Vector similarity
   - Embedding models comparison

5. [05-langchain-basics.ipynb](./07-llm-basics/05-langchain-basics.ipynb) - **2-3 hours**
   - LangChain fundamentals
   - Chains and prompts
   - Memory management
   - Basic RAG patterns

---

## 🎯 Learning Path

### Timeline (4-5 weeks at moderate pace)

```
Week 1: Mathematics (10-12 hours)
  Module 4: Linear Algebra, Calculus, Probability
  
Week 2: Data Science (12-14 hours)
  Module 5: EDA, Cleaning, Visualization, SQL
  
Week 2-3: ML Libraries (12-14 hours)
  Module 6: scikit-learn, Feature Engineering, Pipelines
  
Week 3-5: LLM Fundamentals (15-18 hours) ⭐
  Module 7: Transformers, LLMs, Prompting, LangChain
```

### Alternative: Goal-Based Paths

**Path A: Data Science Focus**
```
4 → 5 → 6 → (Optional: 7)
Focus on traditional ML and data analysis
Best for: Data analyst roles, business analytics
```

**Path B: AI/LLM Focus** ⭐ RECOMMENDED FOR 2024+
```
4 → 7 → (Then skip 5,6 if short on time)
Focus on LLMs and modern AI
Best for: LLM engineers, AI product roles, startup tech
```

**Path C: Full Stack** (Recommended)
```
4 → 5 → 6 → 7
Complete everything for versatility
Best for: Senior roles, product leadership, flexibility
```

---

## 📈 Time Breakdown by Module

| Module | Hours | Type | Difficulty |
|--------|-------|------|-----------|
| 4-Mathematics | 10-12 | Theory+Code | ⭐⭐⭐ Medium-High |
| 5-DataScience | 12-14 | Hands-On | ⭐⭐ Medium |
| 6-MLLibraries | 12-14 | Hands-On | ⭐⭐ Medium |
| 7-LLMBasics | 15-18 | Theory+Code | ⭐⭐⭐ Medium-High |
| **Total** | **49-60** | **Mixed** | **Medium** |

---

## ✅ Success Criteria

**You'll succeed at Level 2 if you can**:

✅ **Mathematics**:
- Explain matrix operations and their ML applications
- Derive and implement gradient descent
- Conduct statistical tests on data

✅ **Data Science**:
- Identify and handle data quality issues
- Create exploratory visualizations
- Query databases with SQL
- Tell a data story

✅ **ML Libraries**:
- Build scikit-learn pipelines
- Tune models with GridSearch
- Evaluate models comprehensively
- Handle real-world messy data

✅ **LLMs** ⭐:
- Explain transformer architecture
- Compare LLM models for different tasks
- Write effective prompts
- Integrate LLMs into applications
- Build basic LangChain applications

---

## 🛠️ Setup & Environment

### Requirements
```
Python 3.9+
Jupyter Notebook
Packages: numpy, pandas, scikit-learn, matplotlib, seaborn
LLM Access: OpenAI API key (or use free alternatives)
```

### Quick Setup
```bash
# Clone the course
git clone <course-repo>
cd LEVEL-2-INTERMEDIATE

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install requirements
pip install -r requirements.txt

# Start Jupyter
jupyter notebook
```

### LLM API Setup
**For Module 7 (LLM Basics)**:
- [OpenAI API Key](https://platform.openai.com/api-keys) - Free $5 trial
- [Anthropic Claude](https://console.anthropic.com) - Free tier available
- [HuggingFace](https://huggingface.co) - Free models
- [Local Ollama](https://ollama.ai) - Completely free, no API needed

---

## 📖 Learning Tips

### For Mathematics Module
- 📝 Work through proofs step-by-step
- 🖥️ Implement algorithms from scratch
- 📊 Visualize mathematical concepts
- ⏸️ Don't memorize, understand intuition

### For Data Science Module
- 📈 Use real datasets from Kaggle
- 🔍 Ask questions: "Why?", "What if?"
- 📋 Document your analysis process
- 🎨 Focus on clear visualizations

### For ML Libraries Module
- 🔄 Experiment with different algorithms
- 📊 Compare performance metrics
- 🧪 Use cross-validation always
- 📱 Build end-to-end pipelines

### For LLM Module ⭐
- 🤖 Experiment with different prompts
- 🔑 Try multiple LLM models
- 📚 Read model documentation
- 🏗️ Build practical applications
- 🧠 Understand model limitations

---

## 🔗 Module Navigation

| Module | Start | Time | Level |
|--------|-------|------|-------|
| [📐 Module 4: Mathematics](./04-mathematics-for-ml/README.md) | Start here for theory-heavy content | 10-12 hrs | ⭐⭐⭐ |
| [📊 Module 5: Data Science](./05-data-science-analysis/README.md) | For practical analytics | 12-14 hrs | ⭐⭐ |
| [🤖 Module 6: ML Libraries](./06-ml-libraries/README.md) | For scikit-learn deep dive | 12-14 hrs | ⭐⭐ |
| [🧠 Module 7: LLM Basics](./07-llm-basics/README.md) | **NEW - For AI/LLM focus** | 15-18 hrs | ⭐⭐⭐ |

---

## 📚 Resources

### Mathematics
- [3Blue1Brown: Essense of Linear Algebra](https://www.3blue1brown.com/essence-of-linear-algebra)
- [MIT: Linear Algebra (Gilbert Strang)](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [MIT: Calculus for ML](https://ocw.mit.edu/courses/18-01-single-variable-calculus-fall-2006/)

### Data Science
- [Kaggle Datasets](https://kaggle.com/datasets)
- [Data Science Handbook](https://www.oreilly.com/library/view/python-data-science/9781491912058/)

### ML Libraries
- [Scikit-learn Official Docs](https://scikit-learn.org)
- [Feature Engineering Book](https://www.oreilly.com/library/view/feature-engineering-for/9781491953235/)

### LLMs ⭐
- [Attention is All You Need Paper](https://arxiv.org/abs/1706.03762)
- [OpenAI Docs](https://platform.openai.com/docs)
- [Anthropic Claude Docs](https://docs.anthropic.com)
- [LangChain Docs](https://python.langchain.com)
- [DeepLearning.AI: Short Courses](https://deeplearning.ai)

---

## 🎓 Completion Certificate

Upon completing all modules at Level 2, you'll earn:
- ✅ Certificate of Intermediate Proficiency
- ✅ Portfolio-ready projects
- ✅ Ready for Level 3 (Advanced)
- ✅ Job-ready ML engineering skills

---

## ❓ FAQ

**Q: How fast can I complete Level 2?**
A: 2-3 weeks at intensive pace, 4-5 weeks at moderate pace, or pick modules individually.

**Q: Can I skip Module 4 (Mathematics)?**
A: Not recommended. Math is foundation for everything else. Minimum: understand key concepts.

**Q: Should I focus on Data Science or LLMs?**
A: In 2024, LLMs are more immediately valuable. Recommend: Do Module 7 (LLMs) first, then optionally 5-6.

**Q: Do I need API keys?**
A: For Module 7 yes, but free options available (Ollama, HuggingFace free tier, OpenAI free $5).

**Q: Can I get help?**
A: Check README files in each module and exercise instructions for support resources.

---

## 🔗 Navigation

**← Back**: [Main Course Hub](../00-START-HERE.md)  
**↓ Next**: Choose a module above or [Level 3: Advanced](../LEVEL-3-ADVANCED/LEVEL-3-START.md)  

---

**Status**: Level 2 Ready to Start 🚀  
**Prerequisite**: Level 1 Complete ✅  
**Total Time**: 49-60 hours  
**Difficulty**: Medium ⭐⭐  

