# Raed Karkoub

```python
class RaedKarkoub:
    def __init__(self):
        self.name = "Raed Karkoub"
        self.role = "Builder"
        self.background = "Applied Data Science @ Penn State"

    def about(self):
        return (
            "I like building things that actually get used and makes people's life easier. Most of what I work on "
            "starts as something that to solve a problem I or someone I know came across, and I try to turn it into "
            "something simple, fast, and useable. What keeps me motivated is how much you can achieve with an idea "
            "and a computer, and all it takes is time, effort and a willingness to learn"
        )

    def interests(self):
        return [
            "real estate intelligence",
            "financial data systems",
            "student platforms"
        ]

    def stack(self):
        return [
            "Python", "TypeScript", "SQL",
            "FastAPI", "Firebase", "Docker",
            "Pandas", "PyTorch", "FAISS",
            "LLMs", "RAG pipelines"
        ]


def projects():
    return [
        {
            "name": "CampusCribs",
            "desc": (
                "Student housing marketplace built to unify listings, roommate matching, "
                "and direct communication with property managers in one platform"
            ),
            "details": [
                "designed multi-role system (students, listers, managers)",
                "built messaging, search, filtering, and compatibility scoring",
                "architected backend and database for scalability (10K+ listings)",
                "focused on clean UX and useful features"
            ],
            "stack": ["FlutterFlow", "Firebase", "Python"]
        },
        {
            "name": "Fidelity Parser",
            "desc": (
                "Hybrid LLM + state-machine pipeline converting messy multi-page "
                "financial PDFs into structured, analysis-ready datasets"
            ),
            "details": [
                "99.2% row-level extraction accuracy, 99.8% reconciliation accuracy",
                "tracks account context, sections, and transaction types across pages",
                "handles merged rows, split lines, and continuation records",
                "automated validation against statement totals"
            ],
            "stack": ["Python", "pdfplumber", "LLMs"]
        },
        {
            "name": "NYC Price Intelligence",
            "desc": (
                "Multi-source rental scraping and pricing analysis system for NYC real estate data"
            ),
            "details": [
                "uses Crawl4AI for dynamic scraping across listing platforms",
                "handles anti-bot protection via persistent Cloudflare cookie sessions",
                "aggregates and normalizes listings into a unified dataset",
                "performs price-per-sqft analysis, trends, and anomaly detection",
                "designed for scalable ingestion + future predictive modeling"
            ],
            "stack": ["Python", "Crawl4AI", "Playwright", "Pandas", "SQL"]
        },
        {
            "name": "Garment Retrieval Engine",
            "desc": (
                "Semantic search system over large-scale garment design datasets"
            ),
            "details": [
                "processed 25K+ YAML/JSON design files",
                "generated dense embeddings using SentenceTransformers",
                "indexed with FAISS for fast top-k similarity search",
                "deployed real-time retrieval API with FastAPI + cloud infrastructure"
            ],
            "stack": ["Python", "SentenceTransformers", "FAISS", "FastAPI"]
        }
    ]


def experience():
    return [
        "Noema Consulting —  Data Scientist / AI Engineer (2025–Present)",
        "Rice University — Research Intern (2024)"
    ]


def main():
    me = RaedKarkoub()

    print(f">> {me.name}")
    print(f"{me.role} | {me.background}\n")

    print(">> about")
    print(me.about(), "\n")

    print(">> interests")
    for i in me.interests():
        print(f"- {i}")
    print()

    print(">> projects")
    for p in projects():
        print(f"- {p['name']}: {p['desc']}")
    print()

    print(">> experience")
    for e in experience():
        print(f"- {e}")
    print()

    print(">> stack")
    print(", ".join(me.stack()), "\n")

    print(">> philosophy")
    print("build things that matter, then make them better")


if __name__ == "__main__":
    main()
