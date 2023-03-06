+++
+++

<section id="hero" class="mb-4">
    <h1 class="text-center" id="slogan">Your note-taking multi-tool</h1>
    <h2 class="text-center">
        Take both text and video notes in a local-first, cloud-optional digital notebook
    </h2>
    <div class="flex flex-col align-items-center w-100">
        <a class="btn btn-lg btn-primary" href="https://squatnotes-cdn.sfo3.cdn.digitaloceanspaces.com/SquatNotes%20Demo-22.2.0.msi">
            <div class="flex align-items-center">
                <i class="text-xxl ti ti-brand-windows"></i>
                <div class="ml-2">
                    <div>Get SquatNotes for Windows</div>
                    <div class="text-sm">Microsoft Installer (.MSI)</div>
                </div>
            </div>
        </a>
        <a class="btn btn-lg btn-secondary mt-1" href="https://squatnotes-cdn.sfo3.cdn.digitaloceanspaces.com/SquatNotes%20Demo-22.2.0.zip">
                    <div class="flex align-items-center">
            <i class="text-xxl ti ti-file-zip"></i>
            <div class="ml-2">
                <div>Download cross-platform bundle</div>
                <div class="text-sm">Requires Java SE 8 or later</div>
            </div>
            </div>
        </a>
    </div>
</section>

{% section(title="Frame-by-frame video notetaking", image="Video Notetaking Screenshot.png", image_left=true) %}
Are you tired of rewinding and fast-forwarding through 30-minute long tutorial videos, trying to remember where a specific instruction was mentioned?

Do you find yourself taking screenshots of videos and pasting them into Word documents so you can take notes?

If so, SquatNotes is for you. [Learn more about SquatNotes' video taking abilities.](pages/video)
{% end %}

{% section(title="Information, at your fingertips", image="Notebook Video Listings.png") %}
Notes aren't useful if you can't find them, yet many apps force you to organize your notes in a particular fashion.

SquatNotes provides many of the organizational features you're used to and then some:
 * Notebooks
 * Sections and subpages
 * Tags (within notebooks)
 * Links between notes (that don't get broken when you rename things)
{% end %}

## Own Your Notes
Your notes are stored locally, so you <a href="https://techcrunch.com/2016/12/14/evernotes-new-privacy-policy-allows-employees-to-read-your-notes/">don't have to
worry about a nosy employee reading what you put in your personal journal</a>, and our [privacy policy](/pages/privacy) is easy to digest.

### Really own your notes
"Own your notes" wasn't just a statement about privacy, but also about the actual format your data is stored in. Throughout the short history of modern computing, many apps have come and gone and so have the proprietary file formats associated with them. Without the app that created your data, all you are left with is an incomprehensible mess of 0s and 1s.

SquatNotes primarily stores your data using human readable JavaScript Oriented Notation (JSON) files. This data format drives the modern web, and is used by almost every website you visit. For more advanced users, the usage of JSON provides an opportunity to create custom scripts for whatever desired purpose.