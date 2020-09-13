# VideoAI

A project inspired from [First-order Motion modeling](https://github.com/AliaksandrSiarohin/first-order-model).
Deals with taking in a video driver & image element and blending them to make a video-over-static-image overlap.

## Results

<video width="300" height="300" controls><source src="samples/result0.mp4" type="video/mp4"></video>
<video width="300" height="300" controls><source src="samples/result1.mp4" type="video/mp4"></video>
<video width="300" height="300" controls><source src="samples/result2.mp4" type="video/mp4"></video>

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.
```bash
pip install -r requirements.txt
```

## Usage

For development server, use the command:
```bash
python main.py
```
For production usage, the app can be run with `gunicorn` wsgi server:
```bash
gunicorn main:app
```
This project supports Heroku deployment (refer `./Procfile`)

## Demo

-   **Gallery**: Watch a list of videos already created

    <img src="samples/videoai_gallery.png" alt="Gallery page" width="800"/>


-   **Templates**: Use a template to try out the process

    <img src="samples/videoai_templates.png" alt="Templates page" width="800"/>


-   **Processing**: Takes a minute or two to complete processing on GPU backend and produce result

    <img src="samples/videoai_processing.png" alt="Templates page" width="800"/>