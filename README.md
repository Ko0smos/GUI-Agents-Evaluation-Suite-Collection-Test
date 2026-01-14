# GUI-Agents-Evaluation-Suite-Collection-Test

A collection of information about the HuggingFace GUI Agents Evaluation Suite, specifically focusing on desktop environment-related Grounding benchmarks.

## Desktop Environment Grounding Benchmarks

- **OSWorld-G**: https://huggingface.co/datasets/MMInstruction/OSWorld-G

### About OSWorld-G

OSWorld-G is a desktop grounding benchmark that is part of the GUI Agents evaluation suite. It contains 510 test samples focused on GUI element grounding tasks in desktop environments including:

- LibreOffice applications (Writer, Calc, Impress)
- GIMP (image editing)
- VS Code
- Terminal applications
- File managers
- System settings

The benchmark tests agents' ability to locate and identify GUI elements within desktop application screenshots, which is a fundamental capability for GUI automation agents.

## Dataset Details

- **Modalities**: Image, Text
- **Format**: Parquet
- **Size**: < 1K samples (510 rows)
- **Task Type**: GUI Element Grounding

## Related Resources

- HuggingFace Organization: https://huggingface.co/MMInstruction
- OSWorld Project: https://os-world.github.io/

## Additional OSWorld Variants

While OSWorld-G focuses on grounding, there are other OSWorld datasets for different desktop platforms:

- Ubuntu OSWorld: https://huggingface.co/datasets/xlangai/ubuntu_osworld
- Windows OSWorld: https://huggingface.co/datasets/xlangai/windows_osworld
- MacOS OSWorld: https://huggingface.co/datasets/xlangai/macos_osworld
