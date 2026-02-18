### Structured API Integration

A structured API orchestration project demonstrating **deterministic client–server boundaries**, **third-party data normalization**, and **service-layer abstraction** within a **Vue 3 + Node.js** architecture.

Originally built to explore clean separation of concerns and real-time data integration patterns that later informed AI workflow and systems orchestration work.

### Architectural Intent

This project emphasizes:

- **Strict client–server separation**
- **Deterministic data transformation layers**
- **Third-party API normalization**
- **Service abstraction** for controlled external integration
- **Scalable SPA routing patterns**

> While not AI-based, the system design principles mirror production AI integration patterns: bounded execution, structured data flow, and controlled external dependency handling.

### System Architecture

#### Frontend — Vue 3 (SPA)

- **Composition API–driven** modular component architecture
- **Route-driven** regional segmentation
- **Dedicated service layer** for backend communication
- **Stateless UI rendering** based on normalized API responses
- **Responsive UI** built with Tailwind CSS

#### Backend — Node.js / Express

- **RESTful** region-based endpoints
- **Encapsulated** Google Places API integration
- **Data transformation and normalization** layer
- **Controlled exposure** of third-party data to client

### Data Flow

1. **User selects** geographic region
2. **Frontend service layer** invokes backend endpoint
3. **Backend queries** Google Places API
4. **Raw third-party response** is normalized
5. **Structured payload** returned to client
6. **UI renders** deterministic region-based activity data

This design highlights:

- **External API encapsulation**
- **Clean transformation boundaries**
- **Separation** between presentation and integration layers

### Deployment

Deployed on Render with environment-based configuration and secure API key handling.

- **Frontend**: [https://kauai-guide.onrender.com](https://kauai-guide.onrender.com)
- **API**: [https://kauai-backend.onrender.com/api](https://kauai-backend.onrender.com/api)

### Technologies

**Vue 3 · Composition API · Node.js · Express · Google Places API · Tailwind CSS · REST Architecture · Service Abstraction Patterns**
