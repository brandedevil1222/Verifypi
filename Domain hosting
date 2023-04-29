# : Commenting after a variable's value DOES NOT WORK in .env files.
# In other words, don't to this: `FOO=value # this is a comment`.
# This would give the value "value # this is a comment" to the FOO variable.
# You need to use single-line comments instead, e.g:
# ```
#   # this is a comment:
#   FOO=value
# ```

#
#
#

# Frontend app URL and bare domain name:
FRONTEND_URL=https://Verify.pi.com
FRONTEND_DOMAIN_NAME=verify.pi.com

# Backend app URL and bare domain name:
BACKEND_URL=https://backend.example.com
BACKEND_DOMAIN_NAME=backend.example.com


# Obtain the following 2 values on the Pi Developer Portal (open develop.pi in the Pi Browser).

# Domain validation key:5888a0e6b9fd70a75d682c5066ef88c0b8dae267a1f81f748d02f613d257b1b58cbddd8638dd86011c4491b1b181566e198e508e1cf4921665262faa4f0344e4
DOMAIN_VALIDATION_KEY=todo_developer_portal
# Pi Platform API Key:mob1epgzalzkferf8uef4tmqmzbhzjpidfoxz9ovjtxmra91mrkfquhixdtxvdvb
PI_API_KEY=Verify_developer_prortal

# Generate a random string, or roll your face on the keyboard to fill this value:
SESSION_SECRET=abcd1324_Verifypi

# MongoDB database connection details:
MONGODB_DATABASE_NAME=verifypi
MONGODB_USERNAME=piverify
MONGODB_PASSWORD=rahul1234


# This will be prepended to all container names.
# Changing this will make docker-compose lose track of all your containers.
# Run `docker-compose down` before changing it.
COMPOSE_PROJECT_NAME=pi-verify-aap

# Set this to either "development" or "production" (XXX "staging"?):
ENVIRONMENT=production

# This dirdirectoryectory will be used to store all persistent data needed by Docker (using volumes):
DATA_DIRECTORY=./docker-data

# URL of the Pi Platform API - you should not need to change this.
PLATFORM_API_URL=https://api.minepi.com
