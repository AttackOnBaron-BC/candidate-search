# Candidate Search Application

## Overview

Candidate Search is a web application designed to help employers find and track potential job candidates by browsing through GitHub user profiles.

## User Story

```
AS AN employer
I WANT a candidate search application
SO THAT I can hire the best candidates
```

## Features

- Browse potential candidates from GitHub
- Save promising candidates to a list
- Persistent storage of selected candidates
- Responsive and intuitive user interface

## Acceptance Criteria

1. Initial candidate display
   - On page load, display detailed information for one candidate
   - Include name, username, location, avatar, email, GitHub profile URL, and company

2. Candidate Management
   - "+" button: Save current candidate to potential candidates list
   - "-" button: Skip current candidate without saving
   - Handling of candidate list exhaustion

3. Potential Candidates Page
   - View list of previously saved candidates
   - Persistent storage across page reloads
   - Handling of empty candidate list
  
  ![image](https://github.com/user-attachments/assets/3750e3be-3a28-4852-9303-45ad04ff5ce6)
  ![image](https://github.com/user-attachments/assets/b362193d-2852-475d-8017-9e41093e2eec)


## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)
- GitHub Personal Access Token

## Setup and Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/candidate-search.git
   cd candidate-search
   ```

2. Install dependencies
   ```bash
   npm install
   npm build
   ```

3. Create a `.env` file in the root directory
   ```
   GITHUB_TOKEN=your_personal_access_token
   ```

4. Start the development server
   ```bash
   npm run dev
   ```

## Technologies Used

- TypeScript
- React
- GitHub REST API
- Local Storage
- Render (for deployment)

## Configuration

### GitHub Personal Access Token

1. Visit [GitHub Personal Access Token]([https://github.com/settings/tokens](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-fine-grained-personal-access-token))
2. Generate a new fine grained token with all default setting
3. Add the token to your `.env` file

## Deployment

The application is deployed on Render. Ensure all environment variables are configured in the Render dashboard.

## API Endpoints

- GitHub Users API: Retrieve candidate information
- Local Backend: Manage candidate selection and storage

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/your-username/candidate-search](https://github.com/your-username/candidate-search)
