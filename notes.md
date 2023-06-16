{
  "Program": {
    "title": {},
    "description": {},
    "keywords": {},
    "programNumber": {},
    "onProgramAdded": {
      "required": "true",
      "localData": {},
      "<components>": {}
    },
    "onProgramRemoved": {
      "required": "true",
      "localData": {},
      "<components>": {}
    },
    "onProgramChangePosition": {
      "spatial": "true",
      "paperPoints": {},
      "localData": {},
      "<components>": []
    },
    "onProgramMarkerAdded": {
      "spatial": "true",
      "paperPoints": {},
      "localData": {},
      "<components>": {}
    },
    "onProgramMarkerChangedPosition": {
      "spatial": "true",
      "paperPoints": {},
      "localData": {},
      "<components>": {}
    },
    "onProgramMarkerRemoved": {
      "spatial": "true",
      "paperPoints": {},
      "<components>": {}
    },
    "onProgramWhiskerAdded": {
      "spatial": "true",
      "localData": {},
      "paperPoints": {},
      "<components>": {}
    },
    "onProgramWhiskerChangedLength": {
      "spatial": "true",
      "localData": {},
      "paperPoints": {},
      "minLengthTrigger": {},
      "<components>": {}
    },
    "onProgramWhiskerChangeSide": {
      "spatial": "true",
      "localData": {},
      "paperPoints": {},
      "value": "[top,bottom,left,right]",
      "<components>": {}
    },
    "globalEmitters": {
      "markersAdded": {
        "addedMarkerList": {}
      },
      "markersChangePosition": {
        "changedMarkerList": {}
      },
      "markersRemoved": {
        "removedMarkerList": {}
      },
      "stepTimeEmitter": {}
    },
    "sharedData": {
      "boardModel": {},
      "sceneNode": {},
      "displaySize": {},
      "allMarkers": {}
    }
  },
  "<components>": {
    "boardModel": {
      "modelComponents": {
        "dataProperties": "[string,boolean,number,enumeration]",
        "linkedDataProperties": {}
      },
      "dataComponents": {
        "dataProperties": [
          "string",
          "boolean",
          "number",
          "enumeration"
        ]
      },
      "linkedDataProperties": []
    },
    "boardView": {
      "viewComponents": {
        "<phetnamespace view library>": {}
      }
    }
  }
}