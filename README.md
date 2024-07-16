# OpenRouter model comparison

Gets all supported models from OpenRouter API.  
Lets you compare via regex search.  
Lets you add value (e.g. LMSys Arena Elo) for each model.  
Calculates value per buck.  
Formula: Value/Prompt Token Cost + Value/Completion Token Cost.  
Caches API response.  
Let's you clear the cache (i.e. model prices and custom values).  
View is not mobile optimized.

**Usage example**  
Local: `open index.html`  
Hosted: `openrouter.martinbetz.eu`  
Filter: `gpt|claude|mistral` to compare matching models.

**Screenshot**  
![Screenshot](screenshot.png)
