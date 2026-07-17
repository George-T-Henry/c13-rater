# c13-rater

Static shell for a text-pair validation task. All content (pairs + concept
definitions) is loaded at runtime from a Supabase backend; this repo contains
no dataset. Designed to be embedded in a Prolific study via URL parameters
(`?dataset=...&block=N`; Prolific appends PROLIFIC_PID / STUDY_ID / SESSION_ID).
