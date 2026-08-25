# A1 – [Create Portfolio]

![dream big image](port-testimage.jpg)

## Objective
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>A1 Portfolio Analysis</title>

    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #f4f6f8;
            color: #222;
            line-height: 1.7;
        }

        header {
            background: #111827;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }

        header p {
            color: #d1d5db;
            font-size: 1.05rem;
        }

        nav {
            background: white;
            border-bottom: 1px solid #ddd;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav ul {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            list-style: none;
        }

        nav li a {
            display: block;
            padding: 16px 20px;
            text-decoration: none;
            color: #222;
            font-weight: bold;
        }

        nav li a:hover {
            background: #e5e7eb;
        }

        main {
            max-width: 1000px;
            margin: 40px auto;
            padding: 0 20px;
        }

        .portfolio {
            background: white;
            margin-bottom: 50px;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
        }

        .portfolio h2 {
            font-size: 2rem;
            margin-bottom: 10px;
            color: #111827;
        }

        .source {
            margin-bottom: 30px;
        }

        .source a {
            color: #2563eb;
            text-decoration: none;
            font-weight: bold;
        }

        .source a:hover {
            text-decoration: underline;
        }

        .analysis {
            margin-bottom: 30px;
        }

        .analysis h3 {
            font-size: 1.25rem;
            margin-bottom: 8px;
            color: #374151;
            border-left: 4px solid #2563eb;
            padding-left: 12px;
        }

        .analysis p {
            color: #444;
        }

        footer {
            background: #111827;
            color: #d1d5db;
            text-align: center;
            padding: 25px;
            margin-top: 50px;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 2rem;
            }

            .portfolio {
                padding: 25px 20px;
            }

            nav li a {
                padding: 12px 10px;
                font-size: 0.9rem;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>A1 Portfolio Analysis</h1>
    <p>Engineering Portfolio Evaluation</p>
</header>

<nav>
    <ul>
        <li><a href="#ikbal">Ikbal Nayem</a></li>
        <li><a href="#thanh">Thanh Tran</a></li>
    </ul>
</nav>

<main>

    <!-- IKbal Portfolio -->
    <section class="portfolio" id="ikbal">

        <h2>Ikbal Nayem Portfolio</h2>

        <div class="source">
            <strong>Source:</strong>
            <a href="https://github.com/ikbal-nayem/ikbal-nayem"
               target="_blank">
                GitHub Portfolio
            </a>
        </div>

        <div class="analysis">
            <h3>A. Navigability</h3>

            <p>
                Ikbal’s portfolio is relatively efficient to navigate because
                of its simple GitHub-based layout. The information is divided
                into sections such as About Me, Tech Stack, Recent Projects,
                Certifications, and Contact. The Recent Projects section
                allows a reader to quickly locate projects such as English
                Tutor AI and BD Law AI. However, the portfolio relies heavily
                on scrolling, and some sections provide limited information
                about what can be found within them. Overall, a reader can
                locate the major areas of Ikbal’s work quickly, but more
                detailed project organization could reduce searching time.
            </p>
        </div>

        <div class="analysis">
            <h3>B. Reproducibility</h3>

            <p>
                Ikbal’s portfolio provides enough information to understand
                the general purpose and technologies used in his projects,
                but not enough to fully reproduce the work without additional
                questions. For example, the English Tutor AI project explains
                its functions and identifies technologies such as OpenRouter
                and React. However, it does not provide detailed procedures,
                design constraints, or testing information. Therefore, the
                portfolio only partially satisfies the reproducibility
                requirement.
            </p>
        </div>

        <div class="analysis">
            <h3>C. Evidence of Reasoning</h3>

            <p>
                Ikbal’s portfolio provides more information about the final
                products than the reasoning behind their development. For
                example, the English Tutor AI project explains its grammar
                correction, conversation simulation, and fluency tracking
                features, but does not explain what design requirements led
                to these features, what alternatives were considered, or
                what problems were encountered. Additional information about
                design decisions, testing, revisions, and tradeoffs would
                provide stronger evidence of the engineering process.
            </p>
        </div>

        <div class="analysis">
            <h3>D. Professional Tone</h3>

            <p>
                Ikbal’s portfolio uses concise and appropriate language for
                a workplace setting. It focuses on his technical experience,
                projects, certifications, and skills without unnecessary
                wording. It also uses technical terminology such as RAG,
                PWA, React, OpenRouter API, ChromaDB, and LangChain. This
                makes the portfolio appropriate for an employer or technical
                reviewer evaluating his qualifications.
            </p>
        </div>

    </section>


    <!-- Thanh Portfolio -->
    <section class="portfolio" id="thanh">

        <h2>Thanh Tran Portfolio</h2>

        <div class="source">
            <strong>Source:</strong>
            <a href="https://thanhvtran.com/"
               target="_blank">
                Thanh Tran Portfolio
            </a>
        </div>

        <div class="analysis">
            <h3>A. Navigability</h3>

            <p>
                Thanh’s portfolio uses graphical elements and animations to
                create a personal website experience. Because of the amount
                of information included, a reader may not locate every piece
                of work within the first 60 seconds. However, the website has
                separate tabs for his resume, projects, about section, and
                contact information. The project section also separates each
                project into its own page with structured information. Overall,
                the major sections are easy to access, although the amount of
                content can increase the time needed to locate specific work.
            </p>
        </div>

        <div class="analysis">
            <h3>B. Reproducibility</h3>

            <p>
                Thanh provides extensive information about his projects, with
                each project organized into its own section. The descriptions
                provide useful information about the purpose and technical
                work involved, such as tolerance stack-up analysis, fixture
                design, and finite element analysis. However, the portfolio
                does not consistently provide enough calculations, procedures,
                design files, or testing data for a colleague to reproduce the
                work without asking additional questions. Therefore, it
                partially satisfies the reproducibility requirement.
            </p>
        </div>

        <div class="analysis">
            <h3>C. Evidence of Reasoning</h3>

            <p>
                Thanh provides strong evidence of reasoning throughout his
                projects. His portfolio explains what was done and, in many
                cases, why the work was necessary. For example, his Boeing
                experience describes redesigning and performing finite element
                analysis on a gear for wing actuation, while his Blue Origin
                experience explains how tolerance stack-up analysis and
                fixture design were used to improve assembly. These
                descriptions provide context for the engineering decisions
                rather than only presenting the final results.
            </p>
        </div>

        <div class="analysis">
            <h3>D. Professional Tone</h3>

            <p>
                Thanh’s portfolio uses a mix of informal and technical
                language. His About section includes jokes such as being
                “addicted to machining” and references to laptop problems,
                which gives the site a personal identity but may distract
                from his qualifications when first viewed. However, his
                experience and project sections use technical and
                workplace-appropriate language when describing his engineering
                work. Overall, the technical sections maintain an appropriate
                tone for an employer or engineering reviewer.
            </p>
        </div>

    </section>

</main>

<footer>
    <p>A1 Portfolio Analysis | Mechanical Engineering</p>
</footer>

</body>
</html>


## Analyze


## Decide


## Communicate

