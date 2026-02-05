# Contributing

## Large 3D models (Git LFS)
This repo uses Git LFS for `.stp`/`.step` files in `3DModels/`.

### One-time setup (per machine)
1. Install Git LFS
2. Run:
   
   git lfs install

### Add a new 3D model
1. Copy the `.stp`/`.step` file into `3DModels/`
2. Stage and commit:

   git add 3DModels/your_part.stp
   git commit -m "Add 3D model for <part>"
3. Push:

   git push

### Verify LFS tracking
Run:

   git lfs ls-files

You should see the tracked `.stp`/`.step` files listed.
