# Week 13: Designing a Data Project for Social Impact

## 📚 Overview

Structure professional data projects that teams can collaborate on. Learn repository organization, dependency management, and deployment patterns used in real social impact work.

## 🎯 Learning Objectives

- Get inspired by real-life data stories and investigative journalism
- Structure a data science repository following best practices
- Manage dependencies reproducibly 
- Document projects for collaboration
- Deploy interactive apps (Streamlit or Marimo)
- Learn from real open-source social impact projects

## 🎓 Session Resources

- **Guest Lecture:** [Data Journalism & Storytelling with Data](https://docs.google.com/presentation/d/1aa3jLl0anUHXqzpUhaJkg3eLjrNJ5uKVU0ThYkpe978/edit?usp=sharing) *(by [Alesya Sokova](https://alesyasokol.taplink.ws/), Novaya Gazeta Europe)*
- **[Colab Notebook](https://colab.research.google.com/drive/1qLbRSd5FrsrhdxvSzz5s468SL5T-Ng7n?usp=sharing)** (create your own copy!)
- **Gallery (Marimo):** https://marimo.io/gallery
- **Gallery (Streamlit):** https://streamlit.io/gallery

## 🏗️ Repository Structure

**Minimal layout:**
```
my-project/
├── README.md
├── pyproject.toml          # Dependencies
├── src/my_package/         # Python code
├── notebooks/              # Jupyter/Marimo
├── data/raw & processed/   # Data
├── tests/                  # Unit tests
└── app/                    # Streamlit or Marimo app
```

**Reference:** [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/)

## 📦 Package Management

| Tool | Docs |
|------|------|
| **uv** |  https://docs.astral.sh/uv/ |
| **Poetry** | https://python-poetry.org/docs/ |


---

## 🔗 Real-World Examples

- **DUO (Drug User Outcomes):** https://github.com/s-sahoo/duo — ML for substance use disorder prediction
- **ModernBERT:** https://github.com/AnswerDotAI/ModernBERT — Open-source language model, professional packaging & CI/CD

---

## 🎨 Interactive Dashboards & Apps

**Marimo** (https://marimo.io/)  
Pure Python reactive notebooks. Use for: interactive analysis, shareable reports, board dashboards.

**Streamlit** (https://streamlit.io/)  
Data app framework. Use for: donation dashboards, grant screeners, volunteer tools, real-time trackers.

---

## Workflow: Local → Testing → Deployment

1. **Local dev** → uv for environment management
2. **Testing** → tests (if needed), code formatting
3. **Collaboration** → Git + installation files (requirements / Docker, etc)
4. **Deploy** → Example: [Streamlit Cloud](https://streamlit.io/cloud)

**Detailed guides:** [Poetry docs](https://python-poetry.org/docs/) | [uv docs](https://docs.astral.sh/uv/getting-started/)

---

## 📋 Mini-Deliverable

**Plan a data project for social impact:**

1. Choose a scenario (donation analysis, volunteer matching, grant screening, impact reporting, etc.)
2. Create repo structure
3. Define data pipeline: Raw Data → Processing → Analysis → Insight
4. Choose Streamlit or Marimo for the interface
5. Write README with setup instructions

**Bonus:** Deploy to Streamlit Cloud or create GitHub Actions for testing.

---

## 📚 Resources

**Setup & Best Practices:**
- [Python Packaging Guide](https://packaging.python.org/)
- [Real Python: Project Structure](https://realpython.com/python-application-layouts/)

**Deployment:**
- [Streamlit Cloud](https://streamlit.io/cloud)
- [DigitalOcean](https://www.digitalocean.com/)
- [Docker](https://www.docker.com/)

**Configuration:**
- [Python-dotenv](https://github.com/theskumar/python-dotenv)
- [Pydantic Settings](https://docs.pydantic.dev/latest/concepts/settings/)

---

## 🎯 Key Takeaway

**A well-structured project isn't just about code—it's about making impact reproducible and shareable.**

When your NGO partner, volunteer team, or funding organization can download your code and recreate your analysis in 5 minutes, that's when real collaboration begins. That's where data science becomes social impact.

---

**Previous Week:** [Week 12: Optimize II – LLMs for Decision Support & Automation](../week12/README.md)

**Next Steps:** Keep iterating, share your work open-source, and help others build data projects for good! 🌱
