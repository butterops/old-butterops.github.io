---
header:
  - type: typewriter
    methods:
      - typeString: Open Team & Projects to <strong>learn!</strong>
      - pauseFor: 500
      - deleteChars: 6
      - typeString: <strong>Collaborate!</strong>
      - pauseFor: 500 
      - deleteChars: 12
      - typeString: <strong>Create!</strong>
      - pauseFor: 500
    options:
      loop: false
      autoStart: true
    height: 190
    paddingX: 50
    align: center
    fontSize: 44
    fontColor: white
    
  - type: text
    height: 200
    paddingX: 50
    paddingY: 0
    align: center
    title:
      - Dev Community
    subtitle:
      - Creating free and open sourced solutions, that solves our own problems
    titleColor: 
    titleShadow: true
    titleFontSize: 44
    subtitleColor: 
    subtitleCursive: true
    subtitleFontSize: 20
    spaceBetweenTitleSubtitle: 16
  
  - type: img
    imageSrc: images/header/background.jpg
    imageSize: cover
    imageRepeat: no-repeat
    imagePosition: center
    height: 235
    paddingX: 50
    paddingY: 0
    align: center
    title:
      - Software Community
    subtitle:
      - Creating free and open sourced solutions that solves our own problems
    titleColor:
    titleShadow: false
    titleFontSize: 44
    subtitleColor:
    subtitleCursive: false
    subtitleFontSize: 16
    spaceBetweenTitleSubtitle: 20

  - type: slide
    height: 235
    options:
        startSlide: 0
        auto: 5000
        draggable: true
        autoRestart: true
        continuous: true
        disableScroll: true
        stopPropagation: true
    slide:
      - paddingX: 50
        paddingY: 0
        align: left
        imageSrc: images/header/background.jpg
        imageSize: cover
        imageRepeat: no-repeat
        imagePosition: center
        title:
          - header title1
        subtitle:
          - header subtitle1
        titleFontSize: 44
        subtitleFontSize: 16
        spaceBetweenTitleSubtitle: 20

      - paddingX: 50
        paddingY: 0
        align: center
        imageSrc: images/header/background.jpg
        imageSize: cover
        imageRepeat: no-repeat
        imagePosition: center
        title:
          - header title2
        subtitle:
          - header subtitle2
        titleFontSize: 44
        subtitleFontSize: 16
        spaceBetweenTitleSubtitle: 20

      - paddingX: 50
        paddingY: 0
        align: right
        imageSrc: images/header/background.jpg
        imageSize: cover
        imageRepeat: no-repeat
        imagePosition: center
        title:
          - header title3
        subtitle:
          - header subtitle3
        titleFontSize: 44
        subtitleFontSize: 16
        spaceBetweenTitleSubtitle: 20
---