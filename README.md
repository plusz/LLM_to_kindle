# LLM_to_kindle_with_make_automation
make.com blueprint for publishing on Kindle

The solution follows a logical flow that transforms story ideas into formatted ebooks delivered directly to Kindle devices:


* Story Source: Google Sheets serves as the content management system for story ideas and tracking
* Content Generation: Perplexity AI generates complete stories based on predefined contexts and prompts
* Content Processing: JSON parsing and text manipulation to prepare the content
*Content Storage: WordPress (optional) and Google Drive for persistence and conversion
* Delivery: Amazon SES for reliable email delivery to Kindle devices

The Make.com blueprint orchestrates these components into a cohesive workflow that requires minimal human intervention once
