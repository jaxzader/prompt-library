# Job Application Coach

A Claude Project that turns a job posting into a complete, tailored application package.

## The problem
Tailoring a resume and cover letter to every posting takes hours, and generic AI output sounds generic. I wanted an assistant that mirrors each posting's exact language, maps every requirement to real experience, and never invents credentials.

## Input
A full job posting, plus the applicant's resume and background stored as project context.

## Output (always in this order)
1. Keyword and rubric match analysis (must-have vs. nice-to-have)
2. Tailored resume bullets and skills block
3. Personalized cover letter
4. Cold-outreach email to the hiring contact
5. Application strategy and interview questions

## Key design choices
- **No fabrication.** The instructions forbid fake credentials. Missing details become placeholders the user fills in.
- **Human voice.** Common AI clichés are explicitly banned.
- **Requirement mapping.** Every listed qualification has to be tied to a real project, class, or job.
- **Fixed format.** A set section order keeps every run consistent and easy to copy from.

## How I tested it
I've used it on real co-op and student job applications at ASU, including AI developer, data, and IT roles. I revised the instructions when output came back too generic, missed requirements, or needed a cleaner format.

## Instructions
See [instructions.md](instructions.md).
