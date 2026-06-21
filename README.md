# Ray Tracer

<p align="justify">
A simple ray tracer written in C++. The renderer uses **Anti-Aliasing** and **Defocus blur (Depth of Field)** features and each scene is rendered with different camera angles.
</p>

## Depth of Field test
<p align="justify">
The image on the left was rendered without any Depth of Field. So the camera focuses all the objects in the scene and each of them appears clearly on the final render. But the image on the right uses Depth of Field to mainly focus on the center object so the other two objects in the scene are blurred.
</p>

<img width="49%" height="225" alt="image1" src="https://github.com/user-attachments/assets/872df609-db77-4bdb-b7d5-cf5ea2e1f4d4" />
<img width="49%" height="225" alt="image2" src="https://github.com/user-attachments/assets/4103576b-4077-4eea-b572-d2306967c5d3" />

## Final Render
<p align="justify">
The big red sphere uses **Diffuse** material, so it doesn't have reflection like the other two spheres. Middle sphere uses **Glass** material so it does both reflection and refraction at the same time giving us a flipped reflection of other objects. The green sphere is a **Metal** sphere which acts like a mirror, so it properly reflects other objects in the scene. All the small objects in the scene uses the same three materials.
</p>

<img width="1280" height="720" alt="image3" src="https://github.com/user-attachments/assets/1c9c119f-acba-4c4d-b73b-4533ba6a7ddc" />
<img width="1280" height="720" alt="image4" src="https://github.com/user-attachments/assets/c33aab7a-ee4c-4260-a62a-5b6572049e59" />
