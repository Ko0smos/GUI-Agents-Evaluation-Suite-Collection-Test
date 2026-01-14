# GUI-Agents-Evaluation-Suite-Collection-Test

A collection of desktop environment-related GUI Agents evaluation suite and Grounding benchmarks from HuggingFace.

## Desktop Environment Grounding Benchmarks

This repository collects all desktop environment-related grounding benchmarks for GUI agents. These benchmarks evaluate agents' ability to locate and identify GUI elements within desktop application screenshots.

### Core Desktop Grounding Benchmarks

- OS-Atlas-data: https://huggingface.co/datasets/OS-Copilot/OS-Atlas-data
- ScreenSpot: https://huggingface.co/datasets/rootsautomation/ScreenSpot
- ScreenSpot-v2: https://huggingface.co/datasets/Voxel51/ScreenSpot-v2
- ScreenSpot-Pro: https://huggingface.co/datasets/Voxel51/ScreenSpot-Pro
- WinDeskGround: https://huggingface.co/datasets/Zbao/WinDeskGround
- Aria-UI_Data: https://huggingface.co/datasets/Aria-UI/Aria-UI_Data
- OSWorld-G: https://huggingface.co/datasets/MMInstruction/OSWorld-G
- OSTask-demo: https://huggingface.co/datasets/open-world-agents/OSTask-demo

### Multi-Platform GUI Grounding Datasets

- Click-100k: https://huggingface.co/datasets/mlfoundations/Click-100k
- grounding_dataset: https://huggingface.co/datasets/HelloKKMe/grounding_dataset
- Salesforce/grounding_dataset: https://huggingface.co/datasets/Salesforce/grounding_dataset
- UGround-V1-8k: https://huggingface.co/datasets/zonghanHZH/UGround-V1-8k
- VenusBench-GD: https://huggingface.co/datasets/inclusionAI/VenusBench-GD
- GUI_grounding: https://huggingface.co/datasets/Novylab/GUI_grounding

### Desktop-Specific Training Datasets

- omniact_grounding_filtered: https://huggingface.co/datasets/InfiX-ai/omniact_grounding_filtered
- FiftyOne-GUI-Grounding-Train-with-Synthetic: https://huggingface.co/datasets/Voxel51/FiftyOne-GUI-Grounding-Train-with-Synthetic

## Key Benchmark Details

### OS-Atlas-data
GUI grounding pre-training data for OS-ATLAS foundation action model. Includes desktop and web interface data collected via screenshots with accessibility tools.

### ScreenSpot
Benchmark created by researchers at Nanjing University and Shanghai AI Laboratory for evaluating large multimodal models (LMMs) on GUI grounding tasks.

### ScreenSpot-Pro
Focuses on GUI grounding capabilities in high-resolution professional environments, including 1,581 authentic screenshots spanning 23 professional applications across 5 industries (Development, Creative, CAD, Scientific, and Office) and 3 operating systems.

### WinDeskGround
Authentic Windows desktop environment dataset for GUI grounding tasks, covering commonly used applications with bounding box annotations and referring expressions.

### Aria-UI_Data
Comprehensive dataset covering mobile, desktop, and web platforms with element captions and instructions for GUI grounding and agent training.

### Click-100k
High-quality grounding dataset (100K+ samples) used to train state-of-the-art grounding models for GUI computer-use tasks, pairing screen frames with GUI commands and click coordinates.

### OSTask-demo
Vision-action dataset for desktop agents, focused on OS-level task execution and imitation learning for computer use models.

## Dataset Categories

### By Platform
- **Windows Desktop**: WinDeskGround, ScreenSpot-Pro, OS-Atlas-data
- **Multi-OS Desktop**: ScreenSpot, ScreenSpot-v2, OSTask-demo
- **Ubuntu/Linux**: Aria-UI_Data (Ubuntu subset), OS-Atlas-data

### By Task Type
- **Pure Grounding**: ScreenSpot, ScreenSpot-v2, WinDeskGround, VenusBench-GD
- **Action + Grounding**: Click-100k, OS-Atlas-data, OSTask-demo
- **Professional Applications**: ScreenSpot-Pro

### By Resolution
- **High-Resolution Professional**: ScreenSpot-Pro
- **Standard Desktop**: ScreenSpot, WinDeskGround
- **Cross-Resolution**: UGround-V1-8k

## Related Projects

- **OS-ATLAS**: Foundation Action Model for Generalist GUI Agents (https://arxiv.org/abs/2410.23218)
- **OSWorld**: Unified OS interaction benchmark (https://os-world.github.io/)
- **Aria-UI**: Computer Use and GUI Agent framework (https://github.com/AriaUI/Aria-UI)

## Usage

These datasets can be used for:
- Training GUI grounding models
- Evaluating computer use models
- Research on GUI agents and multimodal agents
- Desktop automation agent development
- Vision-language-action model training

## Additional Resources

### Web-Based Grounding (Related)
- WebClick: https://huggingface.co/datasets/Hcompany/WebClick

### Mobile GUI Grounding (Related)
- guiact_smartphone_test: https://huggingface.co/datasets/Voxel51/guiact_smartphone_test
- AndroidDaily: https://huggingface.co/datasets/stepfun-ai/AndroidDaily
- LearnGUI: https://huggingface.co/datasets/lgy0404/LearnGUI

## Contributing

If you find additional desktop environment GUI grounding benchmarks, please feel free to contribute by opening an issue or pull request.

## License

This is a curated list. Please check individual dataset licenses on their respective HuggingFace pages.
