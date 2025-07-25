# 🌦️ AI-Based Scientific Research Visualizer

This project allows users to **visualize weather data** or any tabular dataset with animated graphs, audio narration, and a downloadable final plot image using **AI-powered tools**. You can upload a `.csv` file, select any two numeric attributes (columns) for the X and Y axes, choose a chart type, and get:
- 📈 An animated video (e.g., Bar Chart, Line Chart, etc.)
- 🔊 Audio narration explaining the plot
- 🖼️ Final chart image

---
## 💡 Unique Highlights

- 💬 Narration adds accessibility for visually impaired users or researchers in audio-only contexts.
- 🎞️ Frame-by-frame animation shows how values evolve over the dataset.
- 🌍 Designed to support scientific research visualizations in a user-friendly and dynamic way.
- ⚙️ Easily extendable to include Stable Diffusion-generated visuals and summaries in the future.

---
## 🚀 Features

✅ Upload any CSV dataset (e.g., `weather.csv`)  
✅ Choose X and Y axis columns dynamically  
✅ Select from 4 chart types:
- Scatter Plot
- Line Chart
- Bar Chart
- Histogram  
✅ Animated chart video output (`.mp4`)  
✅ Auto-generated audio summary using **Google Text-to-Speech** (`.mp3`)  
✅ Downloadable final chart image (`.png`)  
✅ Simple and intuitive **Gradio-based Web UI**

---

## 📊 Example Use Case

Using the provided `weather.csv`, a user can:
- Select `Date` as X-axis and `Temperature` as Y-axis
- Choose "Line Chart"
- View how temperature varies over time with an animated chart and listen to an audio summary explaining the trend

---

## 🛠️ Tools & Technologies Used

| Tool/Library       | Purpose                                 |
|--------------------|------------------------------------------|
| Python             | Programming language                     |
| Pandas             | CSV data handling and manipulation       |
| Matplotlib & Seaborn | Chart generation                        |
| ImageIO            | Animation from frames                    |
| gTTS (Google Text-to-Speech) | Audio narration generation       |
| Gradio             | Web user interface                      |
| FFmpeg             | Required for encoding video              |
| Stable Diffusion (optional setup) | For advanced AI image generation (extendable feature) |

---

## 🧑‍💻 How It Works

1. **Upload CSV File**  
   Upload any tabular dataset (e.g., weather.csv).

2. **Choose X and Y Columns**  
   Select numeric or date columns for X and Y axes.

3. **Select Chart Type**  
   Choose from Scatter, Line, Bar, or Histogram.

4. **Get Outputs**  
   - Animated graph (.mp4)
   - Narration audio (.mp3)
   - Final chart snapshot (.png)

---


