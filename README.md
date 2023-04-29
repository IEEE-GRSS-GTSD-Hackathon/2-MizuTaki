# 2-MizuTaki

# Contents
[Introduction:	](#_toc133684893)

[Problem Statement:	](#_toc133684894)

[Objective:	](#_toc133684895)

[Proposed Solution:	](#_toc133684896)

[Methodology:	](#_toc133684897)

[Sample Dataset:	](#_toc133684898)

[Annotated images:	](#_toc133684901)

[Training	](#_toc133684902)

[Results:	](#_toc133684903)

[Conclusion:	](#_toc133684904)

[Improvements / Future Scope:	](#_toc133684905)

[Reference: ](#_toc133684906)


## <a name="_toc133684893"></a>Introduction:
- Disaster management is the process of preparing for, responding to, and recovering from natural or man-made disasters.
- It involves various measures like risk assessment, emergency preparedness, response, and recovery.
- During emergency, GIS can aid in decision-making by providing real-time spatial data analysis on the location of the disaster, affected populations, and available resources.

## <a name="_toc133684894"></a>Problem Statement:
Developing tools and strategies to improve disaster management. 

## <a name="_toc133684895"></a>Objective:

To develop a application for disaster management (Cyclone) incorporating Sustainable Development Goals (SDGs).

##
## <a name="_toc133684896"></a>Proposed Solution:
Our proposed solution consisting of an objection detection model to identify cyclones from satellite image (SDG #9), hence giving early warning about it.

So that authorities can take appropriate action to minimize the loss. (SDG #11)

SDG #9: INDUSTRY, INNOVATION AND INFRASTRUCTURE
SDG #11: SUSTAINABLE CITIES AND COMMUNITIES


## <a name="_toc133684897"></a>Methodology:


![Picture](https://user-images.githubusercontent.com/52893813/235316219-d0c82e25-e148-4a89-b17c-08f43b347659.png)

## <a name="_toc133684898"></a>Sample Dataset:

MOSDAC (ISRO)


![Picture2](https://user-images.githubusercontent.com/52893813/235316280-9f46d644-9964-428e-a631-05b8b07bdb44.png)


- Source: MOSDAC, INSAT-3D (Collected in 2022)
- No. of images: ~2400

GIBBS (NOAA)

![Screenshot (8)](https://user-images.githubusercontent.com/52893813/235316521-6da09259-e0fb-4e11-915c-4d3ce10b3c70.png)

- Source: METEOSAT-7 





## <a name="_toc133684904"></a>Conclusion:

With this project we can detect the cyclone from satellite images and built an automated waring system to inform us about the cyclone as soon as possible hence respective disaster management steps can be taken to reduce the death toll as well as to be better prepared for the upcoming event.

# <a name="_toc133684905"></a>Improvements / Future Scope:
Our system providing comparable accuracy but can be improved further by adding more training data in various conditions.

This method can be further applied to various other disaster management like Forest Fire, floods, tsunami and droughts incorporating with time series data.

## <a name="_toc133684906"></a>Reference:

- [**https://www.mosdac.gov.in/**](https://www.mosdac.gov.in/)  **(MOSDAC)**
- [**https://docs.ultralytics.com/](https://docs.ultralytics.com/) **(YOLO v8)**
- [**https://www.ncei.noaa.gov/](https://www.ncei.noaa.gov/)  **(NOAA)**
