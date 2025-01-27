# FlightAware to ForeFlight KML Converter

This tool converts FlightAware Track Logs to ForeFlight-compatible KML files. It allows users to enter a FlightAware Track Log URL and download a converted KML file that can be imported into ForeFlight.

![screenshot](custom-user-map.png)

## Link to converter tool

https://abwburns.com/flightaware-to-foreflight/

## Features

- Converts FlightAware URLs with `/tracklog` or `/google_earth` to the `/google_earth` format.
- Fetches and processes KML files to extract flight path coordinates.
- Generates a ForeFlight-compatible KML file for download.
- Provides a simple and user-friendly interface.

## Usage

1. **Enter the link to the tracklog:**
   - For example: `https://www.flightaware.com/live/flight/N724R/history/20240703/2118Z/KFRG/KFRG/tracklog`
2. **Click "Convert" to process the URL.**
3. **Download the converted KML file** by clicking the "Download Converted KML" link.

## Importing to ForeFlight on iOS/iPadOS
1. Download converted file
2. Open the file app, select the file
3. Click the share button and select Foreflight
4. Select Custom Content -> Custom Map Layers
5. Go to Maps -> Layers -> Scroll down to the converted FlightAware file

## Importing to ForeFlight on MacOS
1. Download converted file
2. Airdrop file to iPhone/iPad
3. When the file app appears after downloading from Airdrop -> Click the share button and select Foreflight
4. Select Custom Content -> Custom Map Layers
5. Go to Maps -> Layers -> Scroll down to the converted FlightAware file

## Deleting Custom Map Layers
1. Open ForeFlight.
2. Go to `Custom -> Custom Map Layers`.
3. Delete any existing layers if needed.
4. Import the downloaded KML file as a custom map layer.
