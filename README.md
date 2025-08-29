# Git & GitHub Workshop – Repo 1

Welcome to **Repo 1** of the Git & GitHub Workshop series. This repository introduces students and faculty to Git and GitHub basics through hands-on practice.

---

## Purpose

- Learn **Git basics**: clone, add, commit, push, pull.
- Practice **collaboration** by organizing bio-data files in structured folders.
- Build confidence with GitHub for future advanced repositories.

---

## Folder Structure

```
Repo-1/
├── Students/
│   └── SampleStudent.md
├── Faculty/
│   └── SampleFaculty.md
└── README.md
```

---

## Instructions for Students

1. Navigate to the `Students/` folder.
2. Create a Markdown file named with your **Roll Number** (e.g., `22EI012.md`).
3. Add your bio-data in this format:

```markdown
# Student Bio-Data

**Name:** Your Full Name  
**Roll No.:** Your Roll Number  
**Department:** Your Department  
**Year:** Your Current Year  

**Interests:**  
- Interest 1  
- Interest 2  
- Interest 3  

**Hobbies:**  
- Hobby 1  
- Hobby 2  
- Hobby 3
```

4. Stage, commit, and push your changes:
   ```bash
   git add .
   git commit -m "Added bio-data for [RollNo]"
   git push
   ```
5. Verify your file appears in the repository.

---

## Instructions for Faculty

1. Navigate to the `Faculty/` folder.
2. Create a Markdown file named with your **Employee ID** (e.g., `904641.md`).
3. Add your bio-data in a similar Markdown format as students.
4. Stage, commit, and push your changes (same commands as above).

---

## Learning Outcomes

By completing this repo, you will understand:
- `git clone`: Copy the repo to your local system.
- `git add`: Stage changes for commit.
- `git status`: Check the repo's status.
- `git commit`: Save changes locally.
- `git push`: Upload changes to GitHub.
- `git pull`: Download the latest updates from GitHub.
- `git fetch`: Check for remote updates.

This foundation prepares you for collaborative work in future repositories.

---

## About PY_THODAR

**PY_THODAR** (Python Thodar: தொடர = series/continue) is a collaborative space for students to learn, build, and showcase applications. The goal is to foster continuous learning, collaboration, and creativity, encouraging every student to create and improve their own app by semester's end.