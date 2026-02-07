# Multi-Objective AI Service Quality Optimization (Native AI Wireless Networks)

 Research Context
This project is part of a Ph.D. research study focused on optimizing the quality of service (QoS) and experience (QoE) for Large Language Model (LLM) agents in geo-distributed cloud systems. The evaluator tool measures performance metrics across various chatbots (ChatGPT, Gemini, Copilot, and DeepSeek) to determine the best service provider based on real-time network conditions and academic accuracy.

 Main Features
* **Application-Layer QoS Monitoring**: Measures TTFB, Jitter, and Stability via secure TCP/TLS handshake probes.
* **Real-Time QoE Analytics: Utilizes Playwright and MutationObserver for high-granularity tracking of TTFT (Time to First Token) and E2E delay.
* **Context-Aware Weighting: Allows users to adjust preference weights (λ QoS, λ QoE, λ Academic) for personalized recommendations.
* **Secure Data Sync**: Automatically synchronizes performance metrics to a research cloud (Google Sheets) for statistical analysis.

How to Use
1. Navigate to the [Releases](https://github.com/al-muqarm/llmevaluator/releases)** section of this repository.
2. Download the latest version of `LLM_Evaluator_Final_Pro.exe`.
3. Ensure you have Google Chrome installed on your Windows machine.
4. Run the application, select your profile (Specialization/Level), and click **"Run Evaluation"**.

Notes for Participants
Privacy: All shared network metrics are anonymous and used strictly for academic research purposes.
Bot Detection**: The tool uses a native Chrome channel to minimize CAPTCHA challenges. It is recommended to be logged into your chatbot accounts in your regular browser for a seamless experience.

---

 Author
Abbas M. Ali Al-Muqarm-Ph.D. in Computer Science-Faculty Member at the University of Kufa, Najaf, Iraq* [ResearchGate Profile](https://www.researchgate.net/profile/Abbas-M-Ali-Al-Muqarm-2)
