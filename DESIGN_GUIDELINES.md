# Design Guidelines

{
  "designGuidelines": {
    "colorSystem": {
      "primaryColor": "#007bff",
      "secondaryColor": "#6c757d",
      "accentColor": "#28a745",
      "successState": "#28a745",
      "errorState": "#dc3545",
      "warningState": "#ffc107",
      "backgroundColor": "#f8f9fa",
      "surfaceColor": "#ffffff",
      "textColors": {
        "primary": "#212529",
        "secondary": "#6c757d",
        "onPrimary": "#ffffff"
      }
    },
    "typography": {
      "fontFamilies": {
        "primary": "'Helvetica Neue', Helvetica, Arial, sans-serif"
      },
      "fontSizes": {
        "title": "24px",
        "subtitle": "18px",
        "body": "16px",
        "caption": "12px"
      },
      "lineHeights": {
        "title": "32px",
        "subtitle": "24px",
        "body": "22px",
        "caption": "16px"
      },
      "fontWeights": {
        "light": "300",
        "regular": "400",
        "bold": "700"
      }
    },
    "spacing": {
      "marginAndPaddingScales": {
        "xs": "4px",
        "sm": "8px",
        "md": "16px",
        "lg": "24px",
        "xl": "32px"
      },
      "gridSystem": {
        "columns": 12,
        "gutter": "30px"
      },
      "componentSpacing": "16px"
    },
    "components": {
      "buttonStyles": {
        "default": {
          "backgroundColor": "#007bff",
          "color": "#ffffff",
          "padding": "8px 16px",
          "borderRadius": "4px",
          "fontSize": "14px",
          "fontWeight": "400"
        },
        "hover": {
          "backgroundColor": "#0056b3",
          "color": "#ffffff"
        }
      },
      "inputStyles": {
        "default": {
          "borderColor": "#ced4da",
          "padding": "8px 12px",
          "fontSize": "14px"
        },
        "focus": {
          "borderColor": "#80bdff",
          "boxShadow": "0 0 0 0.2rem rgba(0,123,255,.25)"
        }
      },
      "cardStyles": {
        "default": {
          "backgroundColor": "#ffffff",
          "padding": "16px",
          "borderRadius": "4px",
          "boxShadow": "0 4px 6px rgba(0,0,0,.1)"
        }
      },
      "formStyles": {
        "labelFontSize": "14px",
        "inputMarginBottom": "16px"
      },
      "navigationStyles": {
        "backgroundColor": "#007bff",
        "color": "#ffffff",
        "hoverColor": "#0056b3"
      }
    },
    "animations": {
      "transitions": {
        "button": "background-color 0.3s ease",
        "input": "border-color 0.3s ease"
      },
      "hoverEffects": {
        "button": "background-color lighten 10%",
        "card": "box-shadow increase"
      },
      "loadingStates": {
        "spinnerColor": "#007bff"
      },
      "pageTransitions": {
        "type": "fade",
        "duration": "300ms"
      }
    },
    "responsiveDesign": {
      "breakpoints": {
        "xs": "0px",
        "sm": "576px",
        "md": "768px",
        "lg": "992px",
        "xl": "1200px"
      },
      "mobileFirstApproach": true,
      "gridSystem": {
        "columns": {
          "xs": 4,
          "sm": 8,
          "md": 12
        },
        "gutter": "15px"
      },
      "componentAdaptations": {
        "buttons": {
          "xs": {
            "padding": "4px 8px",
            "fontSize": "12px"
          }
        },
        "forms": {
          "xs": {
            "labelFontSize": "12px"
          }
        }
      }
    }
  },
  "examples": {
    "loginScreen": {
      "layout": "Center align form with title, input fields (email, password) and login button. Use primary color for button and surface color for background.",
      "animations": "Use input focus animation from design guidelines. Button hover effect as specified.",
      "responsive": "Stack inputs vertically with adaptive padding according to screen size. Button width should expand to match input field width on smaller screens."
    },
    "productDetailPage": {
      "layout": "Top section for product image, followed by product title, price, description, and 'Add to Cart' button. Use card style for product details section.",
      "colorScheme": "Use primary color for 'Add to Cart' button and text colors as defined for title, subtitle, and body.",
      "responsive": "Image size and card layout should adapt based on screen width. On smaller screens, image should take full width."
    }
  }
}