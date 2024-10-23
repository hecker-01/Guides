# Hoe kan je je site online zetten?

## Github

Je kan in Plesk een git repo linken aan een folder, dat leg ik hiet uit.

### Stap 1

Zorg ervoor dat je github repo op `public` staat.

#### Ga naar je github repo en bekijk of je repo op public of private staat

<figure><img src=".gitbook/assets/private_repo.png" alt=""><figcaption><p>Je repo is Private, ga verder.</p></figcaption></figure>

<figure><img src=".gitbook/assets/public_repo.png" alt=""><figcaption><p>Je Repo is public, ga naar <a href="publish-site-plesk.md#stap-2">Stap 2</a></p></figcaption></figure>

#### Klik op Settings

<figure><img src=".gitbook/assets/settings.png" alt="Settings"><figcaption><p>Settings</p></figcaption></figure>

#### Verander de visibility

<figure><img src=".gitbook/assets/change_visibility.png" alt="Change visibility"><figcaption><p>Change visibility</p></figcaption></figure>

### Stap 2

De site online zetten

#### Ga naar [Plesk](https://web03.sd-lab.nl:8443/) & Log in

#### Klik op "Git"

<figure><img src=".gitbook/assets/click_git.png" alt="Click git"><figcaption><p>Klik op Git</p></figcaption></figure>

#### Klik "Add Repository"

<figure><img src=".gitbook/assets/add-repo.png" alt="Add repository"><figcaption><p>Voeg een repository</p></figcaption></figure>

#### Kopieer de link van jouw Github repo

<figure><img src=".gitbook/assets/copy_link.png" alt="Copy link"><figcaption><p>Kopieer deze link</p></figcaption></figure>

#### Plak de link hierin

<figure><img src=".gitbook/assets/paste_link.png" alt="Paste link"><figcaption><p>Plak de link hierin</p></figcaption></figure>

#### Verander dit naar `/httpdocs/museum-de-pixel`

<figure><img src=".gitbook/assets/change_this.png" alt="Change this"><figcaption><p>Verander Dit naar /httpdocs/museum-de-pixel</p></figcaption></figure>

#### Klik "Create"

<figure><img src=".gitbook/assets/click_create.png" alt="Click create"><figcaption><p>Klik "Create"</p></figcaption></figure>

### Stap 3

De site updates (pull & deploy)

#### Na een commit moet je zelf de site updaten, dit doe je door op "Pull now" & daarna op "Deploy now"

<figure><img src=".gitbook/assets/update.png" alt="Update"><figcaption><p>Klik hierop om de site te updaten</p></figcaption></figure>

### Stap 4

Je site staat nu online op [https://leerlingnummer.stu.sd-lab.nl/museum-de-pixel](https://leerlingnummer.stu.sd-lab.nl/museum-de-pixel) (vervang leerlingnummer met je leerlingnummer)
