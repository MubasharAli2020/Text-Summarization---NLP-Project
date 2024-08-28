# Text-Summarization---NLP-Project
Comparing different NLP models for text summarization using ROUGE scores.

# Text Summarization Project

## Introduction

This project focuses on building a text summarization tool using various pre-trained models from the `transformers` library. The goal is to compare the performance of different models and determine which one provides the most accurate and coherent summaries. The project is implemented in a Jupyter Notebook using Google Colab.

## Project Overview

### Objectives

- To build a text summarization tool using pre-trained models.
- To compare the performance of different models (BART, Pegasus, T5) using ROUGE scores.
- To document the findings and share the project on GitHub.

### Dataset

The sample text used for summarization is a comprehensive overview of climate change, covering various aspects such as:
- Definition and causes of climate change
- Impacts on global temperatures, sea levels, and ecosystems
- Mitigation and adaptation strategies
- The role of policy and international cooperation

### Models Used

- **BART**: `facebook/bart-large-cnn`
- **Pegasus**: `google/pegasus-xsum`
- **T5**: `t5-base`

## Setup Instructions

### Prerequisites

- Google Colab account
- Basic knowledge of Python and Jupyter Notebooks

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MubasharAli2020/Text-Summarization---NLP-Project.git
   cd your-repo
  
  2.  **Open the Notebook in Google Colab**:
    Upload the notebook to Google Colab or open it directly from GitHub.
3.  **Install Required Libraries**:
       ```bash
       !pip install transformers rouge-score
   
   ## Implementation

### Step 1: Data Preprocessing

The text data is preprocessed to remove unnecessary characters, convert to lowercase, and remove stop words. This step ensures the text is clean and ready for summarization.

### Step 2: Summarization Pipelines

Summarization pipelines are created using the  `transformers`  library for BART, Pegasus, and T5 models. Each model is used to generate summaries for the sample text.

### Step 3: Evaluation

The generated summaries are evaluated using ROUGE scores to quantitatively compare the performance of each model. The ROUGE scores provide a measure of precision, recall, and F-measure for each summary.

## Results

### Summaries

#### BART Summary

```
Climate change refers to significant, long-term changes in the global climate. The term is often used interchangeably with global warming, but climate change encompasses a broader range of changes beyond just rising temperatures. These changes include shifts in weather patterns, precipitation, and more frequent extreme weather events. The Earth’s climate system is influenced by various factors, including solar radiation, volcanic activity, and greenhouse gases. Greenhouse gases trap heat in the atmosphere, creating a “greenhouse effect” that warms the planet. While this effect is natural and necessary for life on Earth, human activities have significantly increased the concentration of t. Since the Industrial Revolution, the concentration of CO2 in the atmosphere has increased by more than 40%. Deforestation and land-use changes also contribute to rising CO2 levels by reducing the number of trees that can absorb CO2. Methane, another potent greenhouse gas, is released during the production and transport of coal, oil, and natural gas. Impacts of climate change are already being felt around the world. Global temperatures have increased by about 1.2°C since the late 19th century. This has led to more frequent and intense heatwaves, which can have severe health impacts, particularly for vulnerable populations. Since 1900, global sea levels have risen by about 20 centimeters (8 inches) Rising sea levels threaten coastal communities and ecosystems, increasing the risk of flooding and erosion. Climate change is altering precipitation patterns, leading to more intense and frequent storms in some regions. Oceans absorb about 30% of the CO2 emitted by human activities, which leads to ocean acidification. This process reduces the pH of seawater, affecting marine life. Climate change is causing shifts in the distribution and behavior of many species. Mitigation involves reducing or preventing the emission of greenhouse gases. Adaptation involves adjusting to the changes that are already occurring or are expected to occur. Some species may face extinction if they cannot cope with the changing conditions. These disruptions can have cascading effects on ecosystems and services they provide to humans. Shifting from fossil fuels to renewable energy sources can significantly reduce greenhouse gas emissions. Investing in energy efficiency and conservation measures can also help reduce energy demand. Implementing carbon pricing mechanisms, such as carbon taxes or cap-and-trade systems, can create economic incentives for reducing emissions. Reforestation and Afforestation: Planting trees and restoring forests can help absorb CO2 from the atmosphere. Protecting existing forests and reducing deforestation are also crucial for maintaining carbon sinks. Adopting sustainable agricultural practices, such as agroforestry, can reduce emissions from the agricultural sector. Adaptation Strategies: Building resilient infrastructure can help communities withstand the impacts of climate change. Upgrading existing infrastructure to withstand extreme weather events is also essential. Water Management: Implementing efficient water management practices, such as rainwater harvesting, water recycling, and improved irrigation technique. Ecosystem-Based Adaptation: Protecting and restoring natural ecosystems, such as wetlands, mangroves, and coral reefs, can provide natural buffers against climate impacts. Community Engagement: Engaging communities in climate adaptation planning and decision-making can ensure that adaptation strategies are locally releva. Governments play a crucial role in setting targets, implementing regulations, and providing funding for climate initiatives. Providing education and resources to communities can also enhance their capacity to respond to climate impacts. International agreements, such as the Paris Agreement, aim to unite countries in the effort to limit global warming. Climate change is one of the most pressing challenges of our time, with far-reaching impacts on the environment, economy, and society. Addressing this challenge requires a comprehensive approach that includes both mitigation and adaptation strategies. By transitioning to renewable energy, protecting natural ecosystems, and building resilient communities, we can work towards a sustainable world. CNN.com will feature iReporter photos in a weekly Travel Snapshots gallery. Please submit your best shots of the U.S. for next week. Visit CNN.com/Travel next Wednesday for a new gallery of snapshots. For more, go to CNN.co/Travel.
```

#### Pegasus Summary

```
Research and Markets has announced the addition of the "Climate Change: A Comprehensive Overview" report to their collection of energy and natural resources market reports and data products. The term climate change is often used interchangeably with global warming, but climate change encompasses a broader range of changes beyond just rising temperatures. Climate change refers to the change in the Earth’s climate caused by human activities, such as the burning of coal, oil, and gas for energy, and the greenhouse effect, in which carbon dioxide is released into the atmosphere to trap heat. Carbon dioxide (CO2) is a greenhouse gas that is released into the atmosphere when the burning of fossil fuels such as coal, oil, and natural gas causes the amount of CO2 in the atmosphere to increase. Methane, another potent greenhouse gas, is released during the production and transport of coal, oil, and natural gas, as wel The United Nations Framework Convention on Climate Change (UNFCCC) defines climate change as "the influence of human activities on the climate of any part of the world." The UNFCCC defines climate change as "the influence of human activities on the climate of any part of the world." The United Nations' Intergovernmental Panel on Climate Change (IPCC) has released its latest assessment of the impact of climate change on the world's land, sea and air, and has warned that global temperatures could rise by more than 2C above pre-industrial levels by the end of the century. Climate change is changing the Earth's climate in some ways, such as increasing the amount of carbon dioxide emitted into the atmosphere and increasing the amount of water available to life on the Earth, such as rivers, lakes, and the oceans, and reducing the amount of carbon dioxide released into the atmosphere. The impact of climate change on the world's species, habitats and economies has been well-established since the Industrial Revolution, and is expected to continue to do so until at least the end of the century, according to the Intergovernmental Panel on Climate Change (IPCC). Key words: climate change, carbon pricing, renewable energy, Transition to renewable energy, energy efficiency, conservation, cap-and-trade, carbon pricing, energy efficiency, energy conservation, energy efficiency, conservation, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy efficiency, energy The UN's Intergovernmental Panel on Climate Change (IPCC) has warned that unless urgent action is taken, the world could face dangerous levels of climate change by the end of the century, unless urgent action is taken to reduce carbon emissions. The United Nations Environment Programme (UNEP) in partnership with the World Resources Institute (WRI) and the International Institute for Environment and Development (IIED) has released a series of factsheets to help countries prepare for the impacts of climate change. Water-based Adaptation: Water-based adaptation strategies can help mitigate the effects of climate change, such as rising sea levels, flooding, droughts, and other water-related impacts.., and help communities cope with the impacts of climate change, such as rising sea levels, flooding, droughts, and other water-related impacts. Key findings from the UN Intergovernmental Panel on Climate Change's (IPCC) latest assessment of the state of climate change in the world, as compiled by the UN Environment Programme (UNEP) and the Intergovernmental Panel on Climate Change (IPCC). The Intergovernmental Panel on Climate Change (IPCC) has released its latest assessment of the impacts of climate change and has called for urgent action to limit global warming to less than 2C above pre-industrial levels and pursue efforts to limit the temperature increase to 1.5C. The UN's Intergovernmental Panel on Climate Change (IPCC) has warned that unless urgent action is taken to curb climate change, the world could face "dangerous" climate change by the end of the century.... and climate-resilient future.
```

#### T5 Summary

```
climate change encompasses a broader range of changes beyond just rising temperatures . primary driver of recent climate change is human activity, particularly the burning of fossil fuels . human activity increases the concentration of carbon dioxide (CO2) into the atmosphere . greenhouse gases, such as carbon dioxide (CO2), methane (CH4), and nitrous oxide (N2O), trap heat in the atmosphere, creating a "greenhouse effect" that warms the planet . human activities have significantly increased the concentration of tetracycline (tc) since the Industrial Revolution, the concentration of CO2 in the atmosphere has increased by more than 40% . deforestation and land-use changes also contribute to rising CO2 levels . methane, another potent greenhouse gas, is released during the production and transport of coal, oil, and natural gas . global temperatures have increased by about 1.2°C (2.2°F) since the late 19th century . this warming has led to more frequent and intense heatwaves, which can have severe health impacts . l as from livestock and other agricultural practices . since 1900, global sea levels have risen by about 20 centimeters (8 inches) rising sea levels threaten coastal communities and ecosystems, increasing risk of flooding and erosion . climate change is altering precipitation patterns, leading to more intense and frequent storms . the oceans absorb 30% of the CO2 emitted by human activities, which leads to ocean acidification . this process reduces the pH of seawater, affecting marine life . climate change is causing shifts in the distribution and behavior of many species . disruptions can have cascading effects on ecosystems and services . mitigation involves reducing or preventing the emission of greenhouse gases . adaptation involves adjusting to the changes that are already occurring or are expected to occur . transitioning from fossil fuels to renewable energy sources can significantly reduce greenhouse gas emissions . carbon pricing mechanisms, such as carbon taxes or cap-and-trade systems, can create economic incentives for reducing emissions. edward mccaffery: reducing carbon emissions is a good way to reduce energy demand . Planting trees and restoring forests can help absorb CO2 from the atmosphere . agroforestry, conservation tillage, and improved livestock management can reduce emissions from the agricultural sector . people to adopt cleaner technologies and practices . th and resilience to climate impacts . infrastructure resilience can help communities withstand the impacts of climate change . water management practices such as rainwater harvesting, water recycling, and improved irrigation technique are essential . th . s, can help address water scarcity and ensure a reliable water supply . wetlands, mangroves, coral reefs can provide natural buffers against climate impacts . community engagement can ensure adaptation strategies are locally relevatable . nt and effective. Providing education and resources to communities can also enhance their capacity to respond to climate impacts . effective climate action requires strong policy frameworks and international cooperation . governments play a crucial role in setting targets, implementing regulations, and providing funding for climate initiatives. o well below 2°C above pre-industrial levels and pursue efforts to limit the temperature increase to 1.5°C . aaron carroll: climate change is one of the most pressing challenges of our time . by transitioning to renewable energy, we can work towards a sustainable future, he says . a climate-resilient future, argues dr. edward mcgahey . he argues that a resilient future is the key to a sustainable and resilient future . and climate change-resistant future.
```

### ROUGE Scores

#### BART ROUGE Scores

```
{'rouge1': Score(precision=0.9435975609756098, recall=0.6522655426765016, fmeasure=0.7713395638629283), 'rougeL': Score(precision=0.8704268292682927, recall=0.6016859852476291, fmeasure=0.7115264797507789)}
```

#### Pegasus ROUGE Scores

```
{'rouge1': Score(precision=0.5552367288378766, recall=0.4077976817702845, fmeasure=0.47023086269744835), 'rougeL': Score(precision=0.30272596843615496, recall=0.22233930453108536, fmeasure=0.2563791008505468)}
```

#### T5 ROUGE Scores

```
{'rouge1': Score(precision=0.9408502772643254, recall=0.5363540569020021, fmeasure=0.6832214765100671), 'rougeL': Score(precision=0.8724584103512015, recall=0.49736564805057953, fmeasure=0.6335570469798657)}
```

### Analysis

Based on the ROUGE scores and the qualitative analysis of the summaries, we found that:

-   **BART**  provided the most coherent and comprehensive summaries with high precision and recall.
-   **T5**  also performed well, generating relevant summaries but with slightly lower recall compared to BART.
-   **Pegasus**  struggled the most, with lower precision and recall, indicating less relevant and comprehensive summaries.

## Conclusion

This project demonstrates the effectiveness of different pre-trained models for text summarization. BART emerged as the best performer, providing a good balance of precision and recall. The project highlights the importance of using evaluation metrics like ROUGE scores to quantitatively compare model performance.

## Future Work

-   **Fine-Tuning**: Fine-tune the models on a specific dataset to potentially improve performance.
-   **User Interface**: Create a simple web interface using tools like Streamlit or Flask to make the summarization tool more interactive.
-   **Additional Models**: Experiment with other pre-trained models available in the  `transformers`  library.

## Acknowledgments

-   Hugging Face for providing the  `transformers`  library.
-   Google Colab for providing the platform to run the Jupyter Notebook.

## License

This project is licensed under the MIT License - see the LICENSE file for details.


