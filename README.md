# Java - Send SMS During Call Tutorial

This project serves as a guide to help you build an application with FreeClimb. Specifically, the project will:

- Accepts incoming calls
- Sends text messages to callers

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up the Tutorial

1. Configure environment variables.

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                          |
   | ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
   | FREE_CLIMB_PHONE_NUMBER | The FreeClimb number that is being used to make a phone call. To learn more go [here](https://docs.persephony.com/docs/getting-started-with-persephony#section-2-get-a-phone-number) |
   | HOST                    | URL where your app is being hosted                                                                                                                                                   |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```
