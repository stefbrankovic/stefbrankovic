# Stefan Branković

Final-year Electrical Engineering student at ETF Belgrade (Signals & Systems, GPA 9.0/10.0),
continuing to MSc studies from October 2026. I work on computer vision and deep learning - 
and lately on measuring whether the models we put in front of other models do what they claim.

**Right now:** research intern at the ETF Robotics Laboratory, building a real-time laboratory
protocol assistant. YOLOv8 finds the instruments, ST-GCN reads the operator's actions off
MediaPipe skeletons, and a finite state machine checks whether the protocol is actually being
followed, with a Franka Emika Panda arm to be integrated on top. 2,100+ images, 5,600+ boxes
across 7 instrument classes and 288 action clips, all recorded and annotated in the lab.
Repo goes public after the defense.

---

### Selected work

**[prompt-injection-guardrail-eval]([https://github.com/stefbrankovic/prompt-injection-guardrail-eval])** - What four production prompt-injection
detectors actually detect. Measured as they ship, no retraining, every detector calibrated to
the same false-alarm budget. An instruction-free wrapper template scores 0.9989. An
English-calibrated threshold blocks 70.7% of harmless Serbian in Latin script and 100% in
Cyrillic. Payloads past a 512-token boundary - predicted from the tokenizer alone, confirmed
behaviourally to six decimal places - are invisible; overlapping-window scanning takes
detection there from 0.05 to 0.98. *PSIML 11, with **[Katarina Bojović]([https://github.com/katarinnaaX])**.

**[cpp-shell-interpreter]([[(https://github.com/stefbrankovic/cpp-shell-interpreter)]])** - A command-line shell built from scratch in C++:
11 built-in commands, hand-written lexer and parser, pipes, I/O redirection and batch
scripting, on an abstract Command/Parser class hierarchy.

**[finstat-ai]([[(https://github.com/stefbrankovic/finstat-ai-google-nexus-hackathon)]])** - SME finance platform built in 36 hours with a team of
five at the Google Nexus Hackathon: bank API integrations, eFaktura, Serbian legal database,
analytics dashboard and an assistant on top. I built the data pipeline, advanced analytics dashboard and delivered the pitch to the jury.

---

### Also

Accepted author, Blue Europe / Alexis de Tocqueville 2026 — *Small States, High Stakes:
Central and Eastern Europe in the Global AI Race.* PSIML 11. IOAA 2022 and a national title in
astrophysics and 2nd place awrads in Mathematics and Physics, which is where all of this started. 
Teaching assistant for Signals & Systems, Digital Signal Processing and Automatic Control.

### Tools

Python · C++ · PyTorch · Hugging Face · YOLOv8 · OpenCV · MediaPipe · NumPy · Pandas ·
Git · Linux · LaTeX · [FILL: ROS2 i MATLAB — zadrži samo ako ih stvarno koristiš sada]

[stefan.brankovic2@gmail.com](mailto:stefan.brankovic2@gmail.com) · [LinkedIn]([FILL: link])
