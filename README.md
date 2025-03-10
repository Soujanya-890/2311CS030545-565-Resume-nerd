2311CS030545-565-Resume-nerd
Resume nerd its  useful to professional resume and cv


impot json
def generate_resume():
    resume = {
        "name": "John Doe",
        "contact": {
            "email": "johndoe@example.com",
            "phone": "123-456-7890",
            "linkedin": "linkedin.com/in/johndoe"
        },
        "summary": "Software engineer with 5+ years of experience in Python development.",
        "skills": ["Python", "Django", "Flask", "SQL", "JavaScript", "Git"],
        "experience": [
            {
                "position": "Software Engineer",
                "company": "TechCorp",
                "duration": "2020 - Present",
                "responsibilities": [
                    "Developed and maintained web applications using Django.",
                    "Optimized database queries for performance improvements.",
                    "Collaborated with cross-functional teams to define project requirements."
                ]
            },
            {
                "position": "Junior Developer",
                "company": "DevSolutions",
                "duration": "2018 - 2020",
                "responsibilities": [
                    "Built RESTful APIs using Flask.",
                    "Implemented unit tests and debugging processes.",
                    "Worked closely with senior developers to improve application architecture."
                ]
            }
        ],
        "education": {
            "degree": "B.Sc. in Computer Science",
            "institution": "University of Tech",
            "year": "2018"
        }
    }
    
    with open("resume.json", "w") as file:
        json.dump(resume, file, indent=4)
    
    print("Resume saved as resume.json")

if _name_ == "_main_":
    generate_resume()
