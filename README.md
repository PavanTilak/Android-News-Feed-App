# Android-News-Feed-App
Display news feed items in the form of list



Features in this Feeds App :

- This app shows feeds in list of rows which contain Image and text.

- Verified Internet connection before making Api call and displayed toast message to connect network.

- Written and verified Espresso UI unit test cases .

- ListView is old , instead of ListView used RecyclerView to display list of items in rows for better performance.

- Used Retrofit and RxJava callback methods for backend Api calls.

- Designed and Implemented UI in such a way to fit in all size android devices.

- All code was properly separated and placed in different packages .It is very much extendable and understandable .

- Added debug logs tased to debug if any issues comes in future.

- All dimensions placed dimensions.xml, colors in colors.xml , strings in strings.xml

- Used Picasa third party libraries to render/display images with the URL

- Displayed text on top of Image and aligned bottom of the image

- Attached App and Screenshots for Quick verification and better understanding of app output.


Below JSON format used to show the list in RecyclerView :
{
    "page": {
        "cards": [
            {
                "card_type": "text",
                "card": {
                    "value": "Hello, Welcome to App!",
                    "attributes": {
                        "text_color": "#262626",
                        "font": {
                            "size": 30
                        }
                    }
                }
            },
            {
                "card_type": "title_description",
                "card": {
                    "title": {
                        "value": "Check out our App every week for exciting offers.",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 24
                            }
                        }
                    },
                    "description": {
                        "value": "Offers available every week!",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 18
                            }
                        }
                    }
                }
            },
            {
                "card_type": "image_title_description",
                "card": {
                    "image": {
                        "url": "https://qaevolution.blob.core.windows.net/assets/ios/3x/Featured@4.76x.png",
                        "size": {
                            "width": 1170,
                            "height": 1498
                        }
                    },
                    "title": {
                        "value": "Movie ticket to Dark Phoenix!",
                        "attributes": {
                            "text_color": "#FFFFFF",
                            "font": {
                                "size": 18
                            }
                        }
                    },
                    "description": {
                        "value": "Tap to see offer dates and rescriptions.",
                        "attributes": {
                            "text_color": "#FFFFFF",
                            "font": {
                                "size": 12
                            }
                        }
                    }
                }
            },
            {
                "card_type": "title_description",
                "card": {
                    "title": {
                        "value": "This is a sample text title v1",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 20
                            }
                        }
                    },
                    "description": {
                        "value": "This is a sample text description v1",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 12
                            }
                        }
                    }
                }
            },
            {
                "card_type": "image_title_description",
                "card": {
                    "image": {
                        "url": "https://qaevolution.blob.core.windows.net/assets/ios/3x/Tuesday2@4.76x.png",
                        "size": {
                            "width": 1170,
                            "height": 1170
                        }
                    },
                    "title": {
                        "value": "25% off merch at t-mobile.com",
                        "attributes": {
                            "text_color": "#FFFFFF",
                            "font": {
                                "size": 20
                            }
                        }
                    },
                    "description": {
                        "value": "Tap to see offer dates and rescriptions.",
                        "attributes": {
                            "text_color": "#FFFFFF",
                            "font": {
                                "size": 13
                            }
                        }
                    }
                }
            },
            {
                "card_type": "title_description",
                "card": {
                    "title": {
                        "value": "This is a sample text title v2",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 20
                            }
                        }
                    },
                    "description": {
                        "value": "This is a sample text description v2",
                        "attributes": {
                            "text_color": "#262626",
                            "font": {
                                "size": 14
                            }
                        }
                    }
                }
            }
        ]
    }
}
