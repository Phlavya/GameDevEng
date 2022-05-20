# GameDevEng
Criação do 1° personagem do jogo no UE5
# API CLI do GitHub

# https://cli.github.com/manual/gh_api

gh api \

  -H "Accept: application/vnd.github.v3+json" \

  /usuários/PHLAVYA/hovercard
  Situação👩‍💼

{

  "contexts": [

    {

      "message": "Owns this repository",

      "octicon": "repo"

    }

  ]

}
{

  "title": "Hovercard",

  "description": "Hovercard",

  "type": "object",

  "properties": {

    "contexts": {

      "type": "array",

      "items": {

        "type": "object",

        "properties": {

          "message": {

            "type": "string"

          },

          "octicon": {

            "type": "string"

          }

        },

        "required": [

          "message",

          "octicon"

        ]

      }

    }

  },

  "required": [

    "contexts"

  ]

}
