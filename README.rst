HEART Testing
=============

::

    $ curl http://35.167.110.150:8080/openid-connect-server-webapp/.well-known/openid-configuration | jq
    {
      "request_parameter_supported": true,
      "claims_parameter_supported": false,
      "introspection_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/introspect",
      "scopes_supported": [
        "openid",
        "profile",
        "email",
        "address",
        "phone",
        "offline_access"
      ],
      "issuer": "http://35.167.110.150:8080/openid-connect-server-webapp/",
      "userinfo_encryption_enc_values_supported": [
        "A256CBC+HS512",
        "A256GCM",
        "A192GCM",
        "A128GCM",
        "A128CBC-HS256",
        "A192CBC-HS384",
        "A256CBC-HS512",
        "A128CBC+HS256"
      ],
      "id_token_encryption_enc_values_supported": [
        "A256CBC+HS512",
        "A256GCM",
        "A192GCM",
        "A128GCM",
        "A128CBC-HS256",
        "A192CBC-HS384",
        "A256CBC-HS512",
        "A128CBC+HS256"
      ],
      "authorization_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/authorize",
      "service_documentation": "http://35.167.110.150:8080/openid-connect-server-webapp/about",
      "request_object_encryption_enc_values_supported": [
        "A256CBC+HS512",
        "A256GCM",
        "A192GCM",
        "A128GCM",
        "A128CBC-HS256",
        "A192CBC-HS384",
        "A256CBC-HS512",
        "A128CBC+HS256"
      ],
      "userinfo_signing_alg_values_supported": [
        "HS256",
        "HS384",
        "HS512",
        "RS256",
        "RS384",
        "RS512",
        "ES256",
        "ES384",
        "ES512",
        "PS256",
        "PS384",
        "PS512"
      ],
      "claims_supported": [
        "sub",
        "name",
        "preferred_username",
        "given_name",
        "family_name",
        "middle_name",
        "nickname",
        "profile",
        "picture",
        "website",
        "gender",
        "zoneinfo",
        "locale",
        "updated_at",
        "birthdate",
        "email",
        "email_verified",
        "phone_number",
        "phone_number_verified",
        "address"
      ],
      "claim_types_supported": [
        "normal"
      ],
      "op_policy_uri": "http://35.167.110.150:8080/openid-connect-server-webapp/about",
      "token_endpoint_auth_methods_supported": [
        "client_secret_post",
        "client_secret_basic",
        "client_secret_jwt",
        "private_key_jwt",
        "none"
      ],
      "token_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/token",
      "response_types_supported": [
        "code",
        "token"
      ],
      "request_uri_parameter_supported": false,
      "userinfo_encryption_alg_values_supported": [
        "RSA-OAEP",
        "RSA-OAEP-256",
        "RSA1_5"
      ],
      "grant_types_supported": [
        "authorization_code",
        "implicit",
        "urn:ietf:params:oauth:grant-type:jwt-bearer",
        "client_credentials",
        "urn:ietf:params:oauth:grant_type:redelegate"
      ],
      "revocation_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/revoke",
      "userinfo_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/userinfo",
      "token_endpoint_auth_signing_alg_values_supported": [
        "HS256",
        "HS384",
        "HS512",
        "RS256",
        "RS384",
        "RS512",
        "ES256",
        "ES384",
        "ES512",
        "PS256",
        "PS384",
        "PS512"
      ],
      "op_tos_uri": "http://35.167.110.150:8080/openid-connect-server-webapp/about",
      "require_request_uri_registration": false,
      "code_challenge_methods_supported": [
        "plain",
        "S256"
      ],
      "id_token_encryption_alg_values_supported": [
        "RSA-OAEP",
        "RSA-OAEP-256",
        "RSA1_5"
      ],
      "jwks_uri": "http://35.167.110.150:8080/openid-connect-server-webapp/jwk",
      "subject_types_supported": [
        "public",
        "pairwise"
      ],
      "id_token_signing_alg_values_supported": [
        "HS256",
        "HS384",
        "HS512",
        "RS256",
        "RS384",
        "RS512",
        "ES256",
        "ES384",
        "ES512",
        "PS256",
        "PS384",
        "PS512",
        "none"
      ],
      "registration_endpoint": "http://35.167.110.150:8080/openid-connect-server-webapp/register",
      "request_object_signing_alg_values_supported": [
        "HS256",
        "HS384",
        "HS512",
        "RS256",
        "RS384",
        "RS512",
        "ES256",
        "ES384",
        "ES512",
        "PS256",
        "PS384",
        "PS512"
      ],
      "request_object_encryption_alg_values_supported": [
        "RSA-OAEP",
        "RSA-OAEP-256",
        "RSA1_5"
      ]
    }