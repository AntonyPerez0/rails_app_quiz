    Create a job: POST to http://localhost:3000/jobs with a JSON body of job attributes.

    Show a job: GET http://localhost:3000/jobs/:id.

    List all jobs: GET http://localhost:3000/jobs.

TEST JSON:

{

"url": "https://example.com/job-details",
"employer_name": "Acme Corporation",
"employer_description": "A leading company in innovative products and solutions.",
"job_title": "Software Engineer",
"job_description": "Responsible for developing and maintaining software applications.",
"year_of_experience": 3,
"education_requirement": "Bachelor's degree in Computer Science or related field",
"industry": "Technology",
"base_salary": 85000,
"employment_type_id": 1
}
