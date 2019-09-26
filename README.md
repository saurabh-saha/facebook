# facebook
Facebook Graph API

Access Tokens:
Types- https://developers.facebook.com/docs/facebook-login/access-tokens/#apptokens
Page Access
App Access
User Access
Debug- https://developers.facebook.com/tools/debug/accesstoken/?access_token=EAAUAzuAPO0QBALcCTWdIx2HsltWL8gHRQLIZCIuqEGZB5vzI4hbcp50YdZA02jdVZAS5UGmdPD47c82yN1FzObyxDuhcJMZAxbHKfqPAnfhiAZBYroZBeQJcVekh1PlREJJ5nRuoZA6hlrlCxGFYQLokPoMcJu1157X64g7mumfeyS1VJhssvF9d93a4CZCTrfAIZD&version=v4.0

Webhooks
Add for Page: https://developers.facebook.com/docs/pages/realtime/#set-up-endpoint-and-product

curl -i -X POST \
  -d "access_token=page-access-token" \
  "https://graph.facebook.com/v4.0/{pageid}/subscribed_apps?subscribed_fields=feed"
  
Sample Response
{
  "success": "true"
}
