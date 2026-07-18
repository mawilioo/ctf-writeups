# The best Teh Tarik

- **Category:** OSINT

## Challenge Description

> I was looking through some old memories when one place suddenly came back to my mind.
>
> When I was younger, my father used to take me to a restaurant somewhere around an industrial area. I do not remember the exact date, but I remember the feeling clearly. The parking area was always busy, motorcycles were parked near the front, and we usually sat outside while waiting for our drinks.
>
> The thing I remember most was the teh tarik. Maybe it was not the best teh tarik in the world, but as a kid, it felt special because I always drank it there with my father.
>
> Recently, I passed by the same row of shops again. The building still looked familiar, the road was the same, and the restaurant was still operating. But something felt different. The name on the signboard was no longer the one I remembered.
>
> I tried checking the place again and noticed something strange. The shop name did not change only once. At one point, it had another name too, before becoming the current one. Maybe different owners came and went, or maybe time just moved too fast.
>
> I only have this newer image of the place. However, maps do not always show only the present. Sometimes, they also keep small pieces of the past.
>
> Can you find the earliest restaurant name visible before the later name changes?
>
> Flag format: OPUCC{Name_Of_The_Shop}

## Analysis
### Step 1: Analyze the image
The challenge provided a single image of a restaurant named **Restoran Nor Falah**:
- Located at a corner lot
- Pink coloured building

### Step 2: Searched the restaurant on Google Maps

<img width="2558" height="1358" alt="image" src="https://github.com/user-attachments/assets/39b9d456-64cd-4faa-83ac-90fcd8069ba3" />

Found multiple restaurants named **Restoran Nor Falah**, Picked the correct one based on the given image.

### Step 3: Enter Street View
Rollback to years before to identify the earliest restaurant name visible before the later name changes.

<img width="2560" height="1360" alt="image" src="https://github.com/user-attachments/assets/1cdaaf93-a3a2-4d7f-981d-fad3e1c5a545" />

From the Feb 2014 Street View, it is clear that the earliest name of the restaurant is Restoran Nafih Nasi Kandar


Therefore, the flag is:

```text
OPUCC{Restoran_Nafih_Nasi_Kandar}
```

---

