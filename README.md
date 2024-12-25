# LinkedIn Job Postings Analysis 

## Project Overview
This project analyzes LinkedIn job postings from 2023 and 2024 to identify key industries and companies with high hiring activity. The study supports a talent platform startup, in scaling its business by targeting high-demand sectors and selecting an anchor client. Thermo Fisher Scientific is identified as the ideal candidate for its growth potential, financial stability, and the absence of an Applicant Tracking System (ATS).

## Objectives
1. Identify industries with the highest job market share.
2. Analyze the relationship between average salary, job postings, and job views.
3. Examine geographic trends in job postings and salaries by state.
4. Recommend a reliable anchor client to support the startup's business strategy.

## Data Description
The analysis is based on a dataset comprising over 124,000 LinkedIn job postings, which includes the following key components:
- **Companies**: Details about company size, industry, and specialization.
- **Jobs**: Information on job benefits, skills, salaries, and titles.
- **Mappings**: Links between industries and skills for job classification.
- **Postings**: Metadata on job postings, including location, application type, and views.

### Key Variables
- `job_id`, `company_id`, `title`, `description`
- `max_salary`, `med_salary`, `min_salary`, `pay_period`
- `formatted_work_type`, `remote_allowed`, `views`
- `industry_name`, `company_size`, `employee_count`, `state`

## Methods
1. **Industry Analysis**: Examined job market share by industry.
2. **Company Analysis**: Identified top companies by job postings and analyzed trends in public vs. private companies.
3. **Salary Analysis**: Investigated the effect of average salaries on job postings and views.
4. **Geographic Trends**: Mapped job postings and salary variations by state.
5. **Anchor Client Selection**: Evaluated financial performance and growth potential of shortlisted companies.

## Key Findings
- **Industries**: Healthcare leads with 13.4% job market share.
- **Salary Trends**: No significant relationship between average salary and the number of job postings or views.
- **Geography**: States with higher salaries tend to have more job postings.
- **Anchor Client**: Thermo Fisher Scientific is recommended for its robust financial stability, growth, and absence of ATS adoption.

## Visualizations
The analysis includes:
- Industry job market share (bar charts)
- Company job postings (bar charts)
- Salary trends vs. job postings/views (scatter plots)
- Geographic distribution of jobs and salaries (maps)

## Recommendations
- Target industries like Healthcare, IT Services, and Financial Services.
- Focus on partnering with Thermo Fisher Scientific to leverage their growth and alignment with the platform’s objectives.

## Limitations
- Reliance on LinkedIn data may not represent the entire job market.
- The analysis is limited to job postings from 2023 and 2024, offering a snapshot rather than long-term trends.

## Future Work
- Incorporate data from platforms like Glassdoor and Indeed.
- Analyze regional hiring trends and emerging technology impacts on hiring practices.
- Evaluate evolving industry-specific skill demands.
