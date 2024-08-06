# Multimodal Recommender System
![screenshot](rec1.png | width=100)

## Project Overview
This project aims to build a multimodal recommendation system that leverages both textual and visual data to provide personalized recommendations. The system integrates advanced natural language processing (NLP) and computer vision techniques to analyze and understand user preferences from multiple modalities.

## Key Objectives
Integrate Text and Image Data: Utilize textual descriptions and visual content to generate comprehensive recommendations.
Personalized Recommendations: Assign a set of movies to users and recommend additional movies based on their preferences.
Multimodal Embedding: Use multimodal embedding which alligns the realated text and images close to eachother with the contrastive learning technique
Vector Database: Use vector database to store these embeddings and retrive similar content on the go

## Technologies Used
Text Embedding: OpenAI text embedding model
Image Embedding: multi2vec model from palm
Vector database: Weaviate

## Obtain API Keys:

Sign up and obtain API keys from relevant services (e.g., OpenAI, PaLM).
Set Environment Variables:

```
export MM_EMBEDDING_API_KEY='your_palm_api_key'
export TEXT_EMBEDDING_API_KEY='your_openai_api_key'
export OPENAI_BASEURL='https://api.openai.com/v1'
```
## Conclusion
This project demonstrates the power of combining textual and visual data for building sophisticated recommendation systems. By leveraging advanced machine learning models and a user-friendly interface, the system aims to provide accurate and personalized recommendations to enhance user experience.

## Contributing
Contributions are welcome! Please read the contributing guidelines first.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
