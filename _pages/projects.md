---
title: 'Projects'
excerpt: 'A collection of my software development projects'
author_profile: true
permalink: /projects/
---

<head>
<title>Font Awesome Icons</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css" />
<script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
<style>
.project-card {
    margin-bottom: 2rem;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}
.project-title {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    margin-bottom: 1rem;
}
.project-title a {
    text-decoration: none;
    color: rgba(1, 123, 255, 1);
}
.project-description {
    margin-top: 1rem;
}
.swiper {
    width: 100%;
    height: 300px;
    margin-bottom: 1rem;
}
.swiper-slide img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 4px;
}
</style>
</head>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/chatwithpdf-rag-app/">ChatWithPDF-Rag-App</a></h3>
        <a href="https://chatwithpdf-rag.streamlit.app"><i class="fa fa-globe" style="color:black;"></i></a>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/chatwithpdf-rag-app/image-3.png" alt="ChatWithPDF Interface">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Developed an intelligent PDF chatbot using RAG (Retrieval-Augmented Generation) technology.</em></li>
            <li><em>Integrated Mistral-7B LLM and FAISS vector database for accurate document question-answering.</em></li>
            <li><em>Built with Python, Streamlit, and Hugging Face's ecosystem for natural language processing.</em></li>
            <li><em>Jan 2025 – Mar 2025</em></li>
        </ul>
    </div>
</div>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/bookify/">Bookify</a></h3>
        <a href="https://bookify-front.vercel.app"><i class="fa fa-globe" style="color:black;"></i></a>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/bookify/HomePage1.JPG" alt="Bookify Interface">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/bookify/HomePage2.JPG" alt="Bookify Homepage 2">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/bookify/HomePage3.JPG" alt="Bookify Homepage 3">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/bookify/AllBooksPage.JPG" alt="Bookify All Books">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/bookify/SingleBook.JPG" alt="Bookify Single Book">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Developed a user-friendly online book store using the MERN stack (MongoDB, Express.js, React, Node.js).</em></li>
            <li><em>Implemented secure user authentication with Firebase and a comprehensive admin dashboard.</em></li>
            <li><em>Created features including book catalog, shopping cart, order management, and review system.</em></li>
            <li><em>Dec 2024 – Jan 2025</em></li>
        </ul>
    </div>
</div>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/caption-generator/">Caption Generator</a></h3>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/caption-generator/spalsh_poster.jpeg" alt="Caption Generator Interface">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/caption-generator/Picture1.jpg" alt="Caption Generator Example 1">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/caption-generator/Picture2.jpg" alt="Caption Generator Example 2">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Utilized the `vit-gpt2-image-captioning` model to generate captions for images.</em></li>
            <li><em>Designed a streamlined pipeline for processing images and generating captions efficiently.</em></li>
            <li><em>Implemented and tested various pre-processing and post-processing techniques to enhance caption quality.</em></li>
            <li><em>Oct 2023 – Dec 2023</em></li>
        </ul>
    </div>
</div>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/movie-recommender/">Movie Recommender</a></h3>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/movie-recommender/2.png" alt="Movie Recommender Interface">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/movie-recommender/3.png" alt="Movie Recommender Results">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/movie-recommender/6.jpeg" alt="Movie Recommender Features">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Developed a movie recommender web app using Streamlit to provide personalized movie recommendations.</em></li>
            <li><em>Implemented collaborative filtering and content-based filtering algorithms to suggest movies based on user preferences and movie characteristics.</em></li>
            <li><em>Integrated interactive features such as user input forms and dynamic recommendation updates to enhance user experience.</em></li>
            <li><em>Oct 2023 – Dec 2023</em></li>
        </ul>
    </div>
</div>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/deen-islamic-app/">Deen - An Islamic App</a></h3>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/deen-islamic-app/banner.png" alt="Deen Islamic App Banner">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/deen-islamic-app/logo.png" alt="Deen Islamic App Logo">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/deen-islamic-app/zakat.png" alt="Deen Islamic App Zakat Feature">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Developed "Deen - An Islamic App" using Flutter, providing a comprehensive package of Islamic features.</em></li>
            <li><em>Implemented a mosque finder feature using Google Maps API to help users locate nearby mosques.</em></li>
            <li><em>Included features such as prayer times, Quran recitation, Qibla direction, and Islamic calendar to serve the diverse needs of the Muslim community.</em></li>
            <li><em>Oct 2023 – Dec 2023</em></li>
        </ul>
    </div>
</div>

<div class="project-card">
    <div class="project-title">
        <h3><a href="/projects/thrifttrade/">ThriftTrade</a></h3>
    </div>
    <div class="swiper">
        <div class="swiper-wrapper">
            <div class="swiper-slide">
                <img src="/assets/images/projects/thrifttrade/Picture1.png" alt="ThriftTrade Interface">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/thrifttrade/Picture2.png" alt="ThriftTrade Features">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/thrifttrade/Picture3.png" alt="ThriftTrade Categories">
            </div>
            <div class="swiper-slide">
                <img src="/assets/images/projects/thrifttrade/Picture4.png" alt="ThriftTrade Items">
            </div>
        </div>
        <div class="swiper-pagination"></div>
        <div class="swiper-button-next"></div>
        <div class="swiper-button-prev"></div>
    </div>
    <div class="project-description">
        <ul>
            <li><em>Developed "ThriftTrade," a second-hand marketplace website using TypeScript, Node.js, and MongoDB.</em></li>
            <li><em>Implemented user authentication and authorization using Firebase for secure transactions.</em></li>
            <li><em>Designed and built RESTful APIs to manage listings, user profiles, and transactions.</em></li>
            <li><em>Integrated a live auctioning feature to enable real-time bidding on items.</em></li>
            <li><em>Jan 2023 – Mar 2023</em></li>
        </ul>
    </div>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
    const swipers = document.querySelectorAll('.swiper');
    swipers.forEach(swiper => {
        new Swiper(swiper, {
            slidesPerView: 1,
            spaceBetween: 30,
            loop: true,
            pagination: {
                el: swiper.querySelector('.swiper-pagination'),
                clickable: true,
            },
            navigation: {
                nextEl: swiper.querySelector('.swiper-button-next'),
                prevEl: swiper.querySelector('.swiper-button-prev'),
            },
        });
    });
});
</script>
