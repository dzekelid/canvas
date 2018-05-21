---
swagger: "2.0"
x-collection-name: Facebook
x-complete: 0
info:
  title: Facebook Get Canvas Carousel
  description: Canvas Carousel
  termsOfService: https://www.facebook.com/policies/
  version: 1.0.0
host: graph.facebook.com
basePath: /v3.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /&#123;canvas-video-id&#125;:
    get:
      summary: Get Canvas Veo
      description: Canvas Video
      operationId: getCanvasVeo
      x-api-path-slug: 123canvasvideoid125-get
      parameters:
      - in: query
        name: bottom_paddingnumeric string
        description: The padding below the element
        type: string
      - in: query
        name: element_group_keystring
        description: The element group key to bundle multiple elements in editing
        type: string
      - in: query
        name: element_typeenum
        description: The type of the elementDefault
        type: string
      - in: query
        name: idnumeric string
        description: The id of the element
        type: string
      - in: query
        name: namestring
        description: The name of the elementDefault
        type: string
      - in: query
        name: styleenum
        description: The presentation style of the video
        type: string
      - in: query
        name: top_paddingnumeric string
        description: The padding above the element
        type: string
      - in: query
        name: videoVideo
        description: The facebook video node
        type: string
      responses:
        200:
          description: OK
      tags:
      - Canvas
      - Veo
  /&#123;canvas-id&#125;:
    get:
      summary: Get Canvas
      description: Canvas
      operationId: getCanvas
      x-api-path-slug: 123canvasid125-get
      parameters:
      - in: query
        name: background_colorstring
        description: Background color of the canvas
        type: string
      - in: query
        name: body_elementslistCanvasPhoto|CanvasHeader|CanvasVideo|CanvasText|CanvasCarousel|CanvasButton|CanvasFooter|CanvasStoreLocator|CanvasProductList|CanvasProductSet|CanvasLeadForm
        description: Body element nodes for the canvas
        type: string
      - in: query
        name: canvas_linkstring
        description: The canvas link for the canvas
        type: string
      - in: query
        name: idnumeric string
        description: ID of the canvas
        type: string
      - in: query
        name: is_hiddenbool
        description: The canvas is hidden or not
        type: string
      - in: query
        name: is_publishedbool
        description: Publish status of the canvas
        type: string
      - in: query
        name: last_editorUser
        description: User who last edited this canvas
        type: string
      - in: query
        name: namestring
        description: Name used to label the canvasDefault
        type: string
      - in: query
        name: ownerPage
        description: Page that owns this canvas
        type: string
      - in: query
        name: update_timeint32
        description: Last updated time of the canvas
        type: string
      responses:
        200:
          description: OK
      tags:
      - Canvas
  /&#123;canvas-button-id&#125;:
    get:
      summary: Get Canvas Button
      description: Canvas Button
      operationId: getCanvasButton
      x-api-path-slug: 123canvasbuttonid125-get
      parameters:
      - in: query
        name: actionCanvasOpenURLAction
        description: The action associated with the button
        type: string
      - in: query
        name: background_colorstring
        description: Color of the button background
        type: string
      - in: query
        name: bottom_paddingnumeric string
        description: The padding below the element
        type: string
      - in: query
        name: button_colorstring
        description: Color of the button
        type: string
      - in: query
        name: button_styleenum
        description: The style of the button
        type: string
      - in: query
        name: deep_linkstring
        description: Deep link destination only for mobile apps          (used for
          mobile install or engagement ads, and app link is supported)
        type: string
      - in: query
        name: element_group_keystring
        description: The element group key to bundle multiple elements in editing
        type: string
      - in: query
        name: element_typeenum
        description: The type of the elementDefault
        type: string
      - in: query
        name: font_familystring
        description: The font family
        type: string
      - in: query
        name: font_sizenumeric string
        description: The size of the font for the text
        type: string
      - in: query
        name: idnumeric string
        description: The id of the element
        type: string
      - in: query
        name: line_heightnumeric string
        description: The line height of the text
        type: string
      - in: query
        name: namestring
        description: The name of the elementDefault
        type: string
      - in: query
        name: rich_textCanvasRichText
        description: The text inside the button
        type: string
      - in: query
        name: text_alignmentenum
        description: The alignment of the text
        type: string
      - in: query
        name: text_colorstring
        description: The color of the text
        type: string
      - in: query
        name: top_paddingnumeric string
        description: The padding above the element
        type: string
      responses:
        200:
          description: OK
      tags:
      - Canvas
      - Button
  /&#123;canvas-carousel-id&#125;:
    get:
      summary: Get Canvas Carousel
      description: Canvas Carousel
      operationId: getCanvasCarousel
      x-api-path-slug: 123canvascarouselid125-get
      parameters:
      - in: query
        name: bottom_paddingnumeric string
        description: The padding below the element
        type: string
      - in: query
        name: child_elementslistCanvasPhoto
        description: The child elements of the carousel
        type: string
      - in: query
        name: element_group_keystring
        description: The element group key to bundle multiple elements in editing
        type: string
      - in: query
        name: element_typeenum
        description: The type of the elementDefault
        type: string
      - in: query
        name: idnumeric string
        description: The id of the element
        type: string
      - in: query
        name: namestring
        description: The name of the elementDefault
        type: string
      - in: query
        name: styleenum
        description: The presentation style of the carousel
        type: string
      - in: query
        name: top_paddingnumeric string
        description: The padding above the element
        type: string
      responses:
        200:
          description: OK
      tags:
      - Canvas
      - Carousel
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---