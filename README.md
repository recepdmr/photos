# photos from @recepdmr

## How to configure Cloudinary environment
This project need these environment variables;
- `NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME` (Name of the Cloudinary cloud)
- `CLOUDINARY_API_KEY` (You can access via Cloudinary dashboard)
- `CLOUDINARY_API_SECRET` (You can access via Cloudinary dashboard)
- `CLOUDINARY_FOLDER` (You should select a specific folder in your Cloudinary cloud. E.g personel)

## How to run 
Firstly, You should install the packages with `yarn`. After that, you should build the application with `yarn build`. Now your application is ready to use to serve. Your application can be run on local environment with `yarn start` command

## Development
You should use `yarn dev` for the development

NOTE: This repo has forked from [Next.js's image gallery](https://github.com/vercel/next.js/tree/canary/examples/with-cloudinary)