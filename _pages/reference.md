---
title: "Reference"
excerpt: "What others think of me"
permalink: /reference/
no_breadcrumbs: true
---

<style>
    /* Mobile - 360px */
    @media only screen and (min-width: 0rem) {
        #linkedin-recommendation {
            padding: var(--sectionPadding);
        }
        #linkedin-recommendation .cs-container {
            width: 100%;
            max-width: 80rem;
            margin: auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            /* 48px - 64px */
            gap: clamp(3rem, 6vw, 4rem);
        }

        #linkedin-recommendation .cs-card-group {
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            /* 16px - 20px */
            gap: clamp(1rem, 2.5vw, 1.15rem);
        }
        #linkedin-recommendation .cs-item {
            list-style: none;
            width: 100%;
            max-width: 39.375rem;
            /* 24px - 32px top & bottom */
            /* 16px - 40px left & right */
            padding: clamp(1.5rem, 3.15vw, 2rem) clamp(1rem, 3.15vw, 2.5rem);
            background-color: #f7f7f7;
            border-radius: 1rem;
            /* prevents padding from adding to height and width */
            box-sizing: border-box;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            flex-direction: column;
            position: relative;
        }
        #linkedin-recommendation .cs-item p {
            font-style: italic;
        }
        #linkedin-recommendation .cs-quote {
            width: 2.5rem;
            height: auto;
            margin-bottom: 2rem;
            display: block;
        }
        #linkedin-recommendation .cs-review {
            line-height: 1.5em;
            margin: 0;
            /* 20px - 40px */
            margin-bottom: clamp(1.25rem, 3vw, 2.5rem);
            color: var(--bodyTextColor);
        }
        #linkedin-recommendation .cs-name {
            line-height: 1.2em;
            font-weight: 700;
            margin: 0;
            /* in case one card has more text than the other, this pushes up against the review text so the name and title are always at the bottom. Only works if parent is a flexbox */
            margin-top: auto;
            color: var(--headerColor);
            display: block;
        }
        #linkedin-recommendation .cs-job {
            line-height: 1.5em;
            margin: 0;
            color: var(--bodyTextColor);
            display: block;
        }
    }
    /* Tablet - 768px */
    @media only screen and (min-width: 48rem) {
        #linkedin-recommendation .cs-card-group {
            flex-direction: column;
            justify-content: space-between;
            align-items: stretch;
        }
    }
</style>

## LinkedIn Recommendations

<section id="linkedin-recommendation">
    <div class="cs-container">
        <ul class="cs-card-group">
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    Xuanken has been an amazing engineer and a star problem solver in our team. He is a quick learner, is persistent and brings a structured and methodical approach to his work. He has helped uplift standardisation of our cloud and app configuration through automation, and has a keen eye for designing efficient and practical solutions. He has been and will be an asset to any team.
                </p>
                <a href="https://www.linkedin.com/in/jeramv" style="text-decoration: none;">
                    <span class="cs-name">Jeram Venkatraaman</span>
                    <span class="cs-job">Data Platforms | CRM | Integration | Consumer Data Right (Open Banking) | Architecture | Technology Strategy & Blueprint definition | Program Portfolio Mgmt</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    I’ve worked with Xuanken for just over two years. Throughout our time working together, he has consistently demonstrated exceptional intelligence and insight. His ability to grasp complex concepts quickly and apply them effectively to solve problems has been invaluable to our team. He is not only quick to understand new ideas but is also adept at identifying innovative solutions to improve productivity and efficiency.
                    <p>[expand]</p>
                    <p>
                    Xuanken possesses an insatiable curiosity and a keen desire to learn and grow. He is always on the lookout for the best approaches to tackle challenges, often going above and beyond to explore new methodologies and technologies. His proactive attitude toward learning has significantly contributed to our team's success and has inspired others to pursue continuous improvement.
                    <br><br>
                    His drive to always learn, improve, innovate, his dedication to finding the best solutions and his ability to lead by example make him an outstanding asset to any organization.
                    </p>
                    <p>[/expand]</p>
                </p>
                <a href="https://www.linkedin.com/in/rasam-shokati" style="text-decoration: none;">
                    <span class="cs-name">☁️ Rasam Shokati</span>
                    <span class="cs-job">Principal Engineer | Cloud | SRE | GCP | K8s | Azure</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    Xuanken is a skilled and efficient DevOps engineer. He has done outstanding work in maintaining infrastructure for development teams in GCP environment. He uplifted and automated infrastructure and management processes using Terraform and atlantis in a very short duration.<br>
                    He is the go to person for admin issues related to airflow , databases , CI/CD tools , kubernetes, cloudrun etc.
                    <p>[expand]</p>
                    <p>
                    He has done development earlier in his career. He does possess good scripting skills that is expected of DevOps engineer.<br>
                    He is not the most talkative person but can be articulate when he needs to be.<br>
                    He is an asset to any team!
                    </p>
                    <p>[/expand]</p>
                </p>
                <a href="https://www.linkedin.com/in/deepak-chakravarthy-govindan-410a65175" style="text-decoration: none;">
                    <span class="cs-name">Deepak Chakravarthy Govindan</span>
                    <span class="cs-job">Senior Data Engineer at Scentre Group</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    Xuanken is a highly skilled and proficient GCP cloud engineer. He was always willing to help and easy to work with. He explained difficult concepts quite easily and always shared knowledge. If I needed any assistance with GCP, he would be the first person I would approach.
                </p>
                <a href="https://www.linkedin.com/in/duncan-rodger-3994a31" style="text-decoration: none;">
                    <span class="cs-name">Duncan Rodger</span>
                    <span class="cs-job">Infra Engineer | DevOps | All things *nix</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    I had the privilege of working alongside Xuanken at Scentre Group, where he consistently impressed me with his technical expertise and problem-solving abilities.<br><br>
                    What truly sets Xuanken apart is his willingness to tackle challenges head-on. He possesses a keen awareness of his strengths and those of his colleagues, actively seeking feedback for continuous improvement.
                    <p>[expand]</p>
                    <p>
                    I highly recommend Xuanken to anyone seeking a talented and dedicated team player.<br><br>
                    Fantastic team member and a pleasure to work with.
                    </p>
                    <p>[/expand]</p>
                </p>
                <a href="https://www.linkedin.com/in/alwynanildsouza" style="text-decoration: none;">
                    <span class="cs-name">Alwyn D'Souza</span>
                    <span class="cs-job">Modern Data Stack | Architecture | AWS Databricks | dbt</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    Working with Xuaken was a joy as he is an approachable and knowledgable colleague, backed by his technicial experience and bouncing idea approach to his problem solving technique. He also values secure-by-design considerations at low\technical level for the projects we had been involved in.
                </p>
                <a href="https://www.linkedin.com/in/chris-thammanukitcharoen" style="text-decoration: none;">
                    <span class="cs-name">Chris Thammanukitcharoen</span>
                    <span class="cs-job">Threat Management and Security Testing - Principal Consultant\Engineer</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    I highly recommend Xuanken for his expertise in Google Cloud Platform (GCP) and Terraform. His ability to architect scalable solutions using GCP services and automate infrastructure with Terraform is impressive. Also, I need to mention another of his hobbies: exploring some open-source tools and putting them into action, which brings some workable solutions to the table for the organization.
                </p>
                <a href="https://www.linkedin.com/in/samtran07" style="text-decoration: none;">
                    <span class="cs-name">Sam Tran</span>
                    <span class="cs-job">Senior Platform Engineer | GCP | Cloud Architect Certified | 10+ years of industry experience</span>
                </a>
            </li>
            <li class="cs-item">
                <img class="cs-quote" aria-hidden="true" src="/assets/images/quote-red.svg" decoding="async" alt="quote icon" width="40" height="33">
                <p class="cs-review">
                    I've worked with Xuanken at Quantium, and even if it was only for a few months, I saw how great a software engineer he was. His technical skills are superb and very well-rounded. We had a diverse tech stack in our project, and he was able to pick up and learn everything in a short period of time. His work was always well thought of and in excellent quality. He was also a team player and a pleasure to work with. I would absolutely recommend Xuanken.
                </p>
                <a href="https://www.linkedin.com/in/oching" style="text-decoration: none;">
                    <span class="cs-name">Deng Ching-Mallete</span>
                    <span class="cs-job">Engineering Lead</span>
                </a>
            </li>
        </ul>
    </div>
</section>

## Reference Letters

Reference letters and recommendations from my kind superiors.

#### Dr. Chris Woodruff

<iframe src="https://drive.google.com/file/d/1HdfE9DH-Yog1i9GRrAsbOjoYvD8HrjzP/preview" width="100%" height="800" style="border: none"></iframe>

#### Prof. Terry Speed

<iframe src="https://drive.google.com/file/d/1SIRJImYvWrBPeoS3bnTKoqOwNmRj8Azu/preview" width="100%" height="800" style="border: none"></iframe>
