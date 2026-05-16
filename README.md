**This readme includes 3 langugues: Eng, Zh, Ko.**

**# Readme English Ver.**

# Automated Audio-to-Text Transcription Tool
An automated audio transcription utility built on Google Colab leveraging
OpenAI's Whisper model, featuring large file chunking and efficient text
synthesis.
## About The Project
This project solves the common issues of memory overflow and sluggish
processing when transcribing long audio files. By using Python to automatically
slice long audio into 15-minute intervals and piping them into the OpenAI
Whisper model, it ensures stable and highly accurate text generation. Ideal for
meeting minutes, lecture transcriptions, and subtitle generation.
## Step-by-Step Workflow
1. **Environment Setup**: Install OpenAI Whisper and required dependencies
(such as ffmpeg).
2. **Audio Ingestion**: Upload the target audio file to the runtime container.
3. **Audio Segmentation**: Automatically slice the audio file into 15-minute
segments to prevent memory crashes.
4. **Batch Transcription**: Transcribe each segment sequentially using the
Whisper model.
5. **Text Consolidation**: Merge the transcribed text from all segments into a
single, cohesive document.
6. **File Export**: Generate and automatically download the final `.txt`
transcript file.
## Tech Stack
- **Language**: Python
- **Core AI Model**: OpenAI Whisper
- **Audio Processing**: Pydub / FFmpeg
- **Platform**: Google Colab

**# Readme Traditional Chinese Ver.**

# 語音自動轉文字工具 (Audio-to-Text Transcription Tool)
一個基於 Google Colab 與 OpenAI Whisper 的自動化音檔轉錄工具,支援大檔案切片與高效文字輸
出。
## 專案簡介
本專案旨在解決長音檔轉錄時常見的記憶體崩潰與速度緩慢問題。透過 Python 自動將長音檔切分成 15
分鐘的片段,並串接 OpenAI Whisper 模型進行逐段轉錄,最終整合輸出完整的文字檔。非常適合用於會
議記錄、演講逐字稿及課程內容整理。
## 開發步驟與工作流程 (Workflow)
1. **環境部署**:安裝 OpenAI Whisper 及音訊處理核心套件(ffmpeg)。
2. **檔案輸入**:上傳需要轉錄的目標音訊檔案。
3. **音訊切片**:自動將音檔精準切割為每 15 分鐘一段,避免模型因單次讀取過大而失敗。
4. **核心轉錄**:使用 Whisper 模型逐段進行高準確度的語音辨識。
5. **資料整合**:將各段落轉錄出的文字依照時間順序無縫合併。
6. **成果匯出**:自動生成並下載最終的 `.txt` 完整逐字稿檔案。
## 使用技術
- **程式語言**: Python
- **核心模型**: OpenAI Whisper
- **音訊處理**: PyAudio / Pydub / FFmpeg
- **執行環境**: Google Colab

**# Readme Korean Ver.**

# 자동 오디오 음성 인식 및 텍스트 변환 툴 (Audio-to-Text Tool)
Google Colab과 OpenAI Whisper 모델을 기반으로 한 대용량 오디오 파일 분할 및 고효율 텍스트 자동
변환 툴입니다.
## 프로젝트 소개
본 프로젝트는 장시간 오디오 파일 변환 시 발생하는 메모리 초과 및 속도 저하 문제를 해결하기 위해 개발되
었습니다. Python을 통해 긴 오디오 파일을 15분 단위로 자동 분할한 뒤, OpenAI Whisper 모델로 순
차적 전사를 진행하여 최종 하나의 텍스트 파일로 통합해 줍니다. 회의록 작성, 강의 녹취록 및 자막 작업에
최적화되어 있습니다.
## 개발 단계 및 워크플로우
1. **환경 설정**: OpenAI Whisper 및 필수 오디오 처리 패키지(ffmpeg) 설치.
2. **파일 업로드**: 변환하고자 하는 오디오 파일 업로드.
3. **오디오 분할**: 단일 파일 처리 부담을 줄이기 위해 오디오를 15분 단위로 자동 슬라이싱.
4. **순차 전사**: Whisper 모델을 사용하여 분할된 각 세그먼트의 음성을 고정밀로 인식.
5. **데이터 통합**: 각 구간에서 추출된 텍스트를 시간 순서대로 무결점 병합.
6. **최종 내보내기**: 완성된 전체 텍스트를 `.txt` 파일로 생성 및 자동 다운로드.
## 사용 기술 Stack
- **Language**: Python
- **Core AI Model**: OpenAI Whisper
- **Audio Processing**: Pydub / FFmpeg
- **Environment**: Google Colab
