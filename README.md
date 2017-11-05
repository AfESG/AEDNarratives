# AEDNarratives

## How to use in AEDWebsite2016

The markdown and images found herein are the sidebar informational content found in the sidebar for the various geographical locations on the African Elephant Database 2016 website ([AEDWebsite2016](https://github.com/AfESG/AEDWebsite2016)). They are included in that repo as a submodule to allow for editing of this content without the need for editors to make changes to the website's source code. 

After making edits to this repo, to include them in the actual site, you must first pull in the latest changes to the AEDWebsite2016 repo by running the following command on that repo:

* `git submodule update --recursive --remote`

You can then ensure the changes have come through by running the local development server on that repo.

Once confirmed, add, commit, and push the submodule change on the AEDWebsite2016 repo.

In order for the changes to 'go live', you must then redeploy the AEDWebsite2016 by following the deployment instructions found in [that repo](https://github.com/AfESG/AEDWebsite2016#deploy)