# Online Shopping Platform using AR

### About

The project consists of mainly 2 stages:
1. Recommendation model building
2. AR virtual try-on

### Input data

The dataset was initially extracted from Kaggle which consisted of nearly 40,000+ entries of the apparels of different categories.
After data cleaning according to our needs & requirements, our final dataset now consists of approx 21,000 inputs of different types of fashion products, which has 5 different categories like article type, color, season, occasion type, & their respective purchase links.

## To use the code, import the following libraries
 1. streamlit: Streamlit library for creating web applications.
 2. pandas: Library for data manipulation and analysis.
 3. numpy: Library for numerical computing.
 4. matplotlib.pyplot: Library for creating plots and visualizations.
 5. Image from PIL: Image module from the Python Imaging Library for working with images.
 6. requests: Library for making HTTP requests.
 7. BytesIO from `io`: A class for reading and writing bytes data in memory.
 8. matplotlib.image: Module for working with images in Matplotlib

## Code working
1. st.set_page_config(): Configuring the layout and title of the Streamlit page.
2. df = pd.read_csv('df2.csv')`: Reading data from a CSV file named 'df2.csv' into a Pandas DataFrame.
3. Setting the title of the web application and creating a sidebar for user interaction.
4. st.title(): Setting the main title.
5. st.sidebar.title(): Setting the title of the sidebar.
6. Using st.sidebar.selectbox() to allow users to select gender, season, usage, subcategory, and article type.

## Output Display Information
 The code generates a web application where users can select their preferences for fashion items through the sidebar. Based on the selected preferences, the application filters the dataset and displays recommendations with images, names, and links for virtual try-on and purchase. Users can navigate through multiple recommendations using the "next" button.

## Technologies Used
1. Unity: Unity is a cross-platform game engine used for developing interactive 3D and 2D content. In this project, Unity serves as the primary development environment for creating AR applications.
2. Vuforia SDK: Vuforia is an AR development platform integrated with Unity, enabling marker-based AR experiences. It provides tools for recognizing and tracking images, objects, and environments, making it suitable for marker-based AR applications.
3. Spark AR: Spark AR is a platform provided by Facebook for creating AR effects for Instagram, Facebook, and other platforms. It offers a range of tools and features for developing AR experiences, including interactive effects, animations, and filters.
4. Lens Studio : Lens Studio provides advanced AR effects and features, including facial recognition and dynamic object placement, along with seamless integration with Snapchat for social media engagement.
