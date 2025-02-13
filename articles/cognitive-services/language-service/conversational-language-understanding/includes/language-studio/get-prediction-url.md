---
titleSuffix: Azure Cognitive Services
services: cognitive-services
author: aahill
manager: nitinme
ms.service: cognitive-services
ms.subservice: language-service
ms.topic: include
ms.date: 05/13/2022
ms.author: aahi
ms.custom: language-service-clu 
---



1. After the deployment job is completed successfully, select the deployment you want to use and from the top menu click on **Get prediction URL**.

    <!--:::image type="content" source="../media/get-prediction-url-1.png" alt-text="A screenshot showing the prediction URL in Language Studio." lightbox="../media/get-prediction-url-1.png":::-->

2. In the window that appears, copy the sample request URL and body into your command line.

3. Replace `<YOUR_QUERY_HERE>` with the actual text you want to send to extract intents and entities from.

    <!--:::image type="content" source="../media/get-prediction-url-2.png" alt-text="A screenshot showing the request URL in Language Studio." lightbox="../media/get-prediction-url-2.png":::-->

4. Submit the `POST` cURL request in your terminal or command prompt. You'll receive a 202 response with the API results if the request was successful.
