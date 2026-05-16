# Content Strategy — Literature By Edumynt

Domain: https://literature.edumynt.com
Audience: competitive exam students + beginners who want simple bilingual explanations.
Core promise: explain literature so clearly that a 5-year-old can understand the idea, while preserving exam keywords.

## Languages
- Every post must exist in `src/content/posts/en/` and `src/content/posts/hi/`.
- Use the same `translationKey` in both files so the theme language switcher connects them.
- Hindi should be natural Hindi in Devanagari script with natural English terms with English terms where students actually use them.

## Categories
- Poetry
- Drama
- Novel
- Literary Terms
- Indian Writing
- British Literature
- Exam Notes

## Publishing standard
- 3 bilingual posts per day.
- No repeated topic unless it is a deeper follow-up with a clearly different search intent.
- Easy language first, SEO second — but both matter.
- Include definition, example, exam angle, common mistakes, mini summary, and FAQ where useful.
- Use MDX only when needed; normal Markdown is fine.

## Learning loop
Record feedback, banned topics, preferred structures, and corrections in `PROJECT_MEMORY.md`. Future AI runs must read that file before writing.

## Hindi language rule
- Hindi posts must use Devanagari Hindi script, not romanized Hindi.
- English subject terms may remain in English where natural for students.
- Correct style: `Psychology क्या है`, `Memory कैसे काम करती है`, `Parts of Speech क्या होते हैं`.
- Avoid romanized style: `Psychology kya hai`, `Memory kaise kaam karti hai`.
