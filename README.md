<pre>
/AI_Research_Assistant/
├── notebooks/
│   ├── 01_Data_Preprocessing.ipynb         # Clean and structure raw data
│   ├── 02_Exploratory_Data_Analysis.ipynb  # Analyze patterns and insights
│   ├── 03_Model_Development.ipynb          # Core ML model implementation
│   ├── 04_Recommendation_System.ipynb      # Paper recommendation engine
│   ├── 05_Summarization_Tool.ipynb         # Paper summarization module
│   ├── 06_Trend_Analysis.ipynb             # Research trends detection
│   ├── 07_Citation_Network.ipynb           # Citation graph analysis
│   ├── 08_User_Interface.ipynb             # Interactive UI development
│   ├── 09_Evaluation.ipynb                 # System performance metrics
│   ├── 10_Deployment.ipynb                 # Production deployment
│   ├── utils.ipynb                         # Helper functions
│   └── visualizations.ipynb                # Data visualization tools
├── data/
│   ├── raw/                               # Original dataset files
│   │   ├── cs_paper_2nd.zip
│   │   ├── id2paper.json
│   │   ├── AutoScholarQuery/
│   │   │   ├── dev.jsonl
│   │   │   ├── test.jsonl
│   │   │   └── train.jsonl
│   │   ├── RealScholarQuery/
│   │   │   └── test.jsonl
│   │   ├── sft_crawler/
│   │   │   └── train.jsonl
│   │   └── sft_selector/
│   │       ├── test.jsonl
│   │       └── train.jsonl
│   └── processed/                         # Cleaned/transformed data
│       ├── cleaned_data.csv
│       ├── features.csv
│       └── summaries.csv
├── models/                               # Trained model artifacts
│   ├── recommendation_model.pkl
│   ├── summarization_model.pkl
│   └── trend_analysis_model.pkl
├── configs/                             # Configuration files
│   ├── model_params.yaml
│   └── system_config.yaml
├── README.md
├── LICENSE
└── requirements.txt</pre>