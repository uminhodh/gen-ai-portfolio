# Creating Authentic and/or AI-Resistant Assessments Using an AI Chatbot

When designing assignments, professors can choose between Authentic and AI-Resistant Assessments, both promoting critical thinking and real-world applications but with different goals and approaches. Authentic assessments are ideal for helping students connect classroom knowledge with real-world applications, while AI-resistant assessments ensure students' work is uniquely their own, encouraging deeper engagement and originality.

## Similarities:

### Critical Thinking:
Both assessments prioritize higher-order thinking skills, encouraging students to analyze, evaluate, and solve complex problems.

### Real-World Relevance:
Both types of assignments can be grounded in real-world applications, allowing students to engage with tasks that resemble challenges they may face in their careers or daily life.

### Higher-Order Skills:
Both approaches focus on helping students develop skills beyond memorization, such as evaluation, creation, and synthesis.

## Differences:

### Goal:
**Authentic Assessment:** The aim is to assess how well students can apply their knowledge and skills to real-world contexts, preparing them for professional scenarios.

**AI-Resistant Assessment:** The goal is to design tasks that cannot be easily completed by AI tools, ensuring that the work reflects the student’s personal insights and original thought.

### Design Focus:
**Authentic Assessments:** These assignments typically mimic professional tasks, such as case studies, projects, or real-life problem-solving exercises, and may involve teamwork or the use of industry-standard tools.

**AI-Resistant Assessments:** These tasks are crafted to challenge AI tools by requiring personal reflection, unique contexts, creative problem-solving, or evolving scenarios that AI cannot easily handle.

### Technology Interaction:
**Authentic Assessments:** May encourage students to use AI or other technologies as part of their research, collaboration, or problem-solving processes, reflecting how professionals use AI tools in real life.

**AI-Resistant Assessments:** Focus on limiting AI's impact, promoting independent thinking and creativity by designing tasks that require original, human insights.

## Examples of Authentic and AI-Resistant Assessments

### 1. Authentic Assessment

**Model Prompt:**

```
You are an expert educator proficient in creating innovative and authentic assessments that enable students to demonstrate and deepen their learning. Your task is design [NUMBER] authentic [FORMATIVE OR SUMMATIVE] assessments for my [GRADE LEVEL AND SUBJECT] curricular unit on [TOPIC]. Each assessment should include:

Task: Define what students are expected to do, including specific guidelines.
Response Format: Specify how students should present their work (e.g., digital story, panel discussion, project proposal).
Real-World Application: Explain how the task mirrors real-world situations or practices.
Verification of Standard Achievement: (Optional) Describe how the assessment will measure student success based on learning objectives.
Meaningful Feedback: Outline the type of feedback students will receive, focusing on learning and improvement.
```

# Example Mind Map

# Example Markmap in Jupyter Book

```{raw} html
<!-- Add the necessary stylesheet for full-width mind map -->
<style>
  svg.markmap {
    width: 100%;
    height: 100vh;
  }
</style>

<!-- Include the Markmap autoloader -->
<script src="https://cdn.jsdelivr.net/npm/markmap-autoloader@0.16"></script>

<!-- Markmap content -->
<div class="markmap">
  <script type="text/template">
    ---
    markmap:
      maxWidth: 300
      colorFreezeLevel: 2
    ---

    # markmap

    ## Links

    - <https://markmap.js.org/>
    - [GitHub](https://github.com/markmap/markmap)

    ## Related

    - [coc-markmap](https://github.com/markmap/coc-markmap)
    - [gatsby-remark-markmap](https://github.com/markmap/gatsby-remark-markmap)

    ## Features

    - links
    - **inline** ~~text~~ *styles*
    - multiline
      text
    - `inline code`
    - Katex - $x = {-b \pm \sqrt{b^2-4ac} \over 2a}$
    - This is a very very very very very very very very very very very very very very very long line.
  </script>
</div>
