# track-it-up

Tracking and versioning of stuff. Easily accessible. 

I am building a resume manager and job application tracker app with these features in mind:
	•	Manage multiple resumes with overlay/diff comparison
	•	Organize resumes by companies, topics, nested folders
	•	Edit resumes dynamically, maintain a bullet point bank with tagging
	•	Use GPT to suggest best bullet points for a job description??
	•	Track job applications (company, JD text, status, applied date, auto rejection after ~30 days)
	•	Highlight ATS keywords and suggest missing ones
	•	Download resumes as PDF or DOCX
	•	UI feels like Notion or Discord (sidebar, folders, smooth hover animations)
	•	Dockerized for easy deployment
	•	Future: add multi user accounts + CLI interface + package as a Tauri desktop app

Intended Tech Stack (This may change)
	•	Frontend: Next.js (App Router) + TypeScript + Tailwind CSS
	•	Backend: Next.js API routes (fullstack), or FastAPI (optional future)
	•	DB: Supabase Postgres + Auth
	•	ORM: Prisma
	•	Testing: Jest + React Testing Library (unit, integration)
	•	Deployment: Vercel + Supabase
	•	Containerization: Docker
	•	Optional: Tauri (for desktop app), CLI with oclif