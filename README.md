### Kauai Travel Helper

Fullstack single-page application integrating the **Google Places API** to explore region-based activity discovery across Kauai.

Built to explore **structured API orchestration**, **client-server separation**, and **real-time third-party data integration** within a **Vue 3 + Node.js** environment.

### Architecture Overview

The application follows a two-tier structure:

#### Frontend (Vue 3 SPA)

- **Composition API–based** component architecture  
- **Route-driven** regional navigation  
- **Service-layer abstraction** for API communication  
- **Responsive UI** built with Tailwind CSS  

#### Backend (Node.js / Express API)

- **RESTful endpoints** for region-based activity queries  
- **Google Places API integration** for real-time activity data  
- **Data transformation layer** to normalize third-party responses before returning to the client  

### Data Flow

1. **User selects** a geographic region  
2. **Frontend calls** Express API endpoint  
3. **Backend queries** Google Places API  
4. **Response data is normalized** and returned to the client  
5. **UI renders** structured activity information  

This design emphasizes **real-time API orchestration** and **clean client-server separation**.

### Live Demo

> Demonstrates real-time Google Places API orchestration and structured client-server separation in a deployed environment

- **Frontend**: [`https://kauai-guide.onrender.com`](https://kauai-guide.onrender.com)
- **API**: [`https://kauai-backend.onrender.com/api`](https://kauai-backend.onrender.com/api)

Deployed on Render with environment-based API key configuration and clean client-server separation.

### Technologies

**Vue 3 · Composition API · Node.js · Express · Google Places API · Tailwind CSS**
