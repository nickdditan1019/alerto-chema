# Alerto PH Firebase Schema

This is the firebase schema for the Alerto PH application.

### Setup

1. Clone the repository:
   ```bash
   git clone git@https://github.com/WiredField/alerto-ph-schema.git
   cd alerto-chema
   ```

2. Generate bundle yaml schema:
   ```bash
   cd openapi
   npx swagger-cli bundle openapi.yaml -o bundled.yaml
   ```
   
### Push yaml file to Redocly
