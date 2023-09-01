---
menu:
  main:
    weight: 7
title: Contact
---
<div style="display: flex; flex-direction: row;">
    <div style="width: 50%; padding-top: 100px;">
        <h3>
            <span style="font-size: large; font-family: georgia, palatino; color: #601a34;">Vous pouvez me contacter par mail :<span>
        </h3>
        <blockquote>
            <address>
                <span style="font-family: georgia, palatino; color: #601a34; font-size: x-large;">mathanath@gmail.com</span>
            </address>
        </blockquote>
        <h3>
            <span style="font-size: large; font-family: georgia, palatino; color: #601a34;">ou me joindre par téléphone au :</span>
        </h3>
        <blockquote>
            <address>
                <span style="font-family: georgia, palatino; color: #601a34; font-size: x-large;">06 30 96 92 44</span>
            </address>
            <address>&nbsp; &nbsp;</address>
            <address>&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;
                <span style="font-family: georgia, palatino; font-size: large; color: #601a34;"><em>Nathalie Fraisse</em></span>
            </address>
        </blockquote>
    </div>
    <div style="width: 50%;">
        <form action="https://formspree.io/f/xjvqrgag" method="post" class="contact_form">
            <fieldset>
                <h3>Envoyez-moi un message</h3>
                <p>
                    <input name="nom" class="text_input" type="text" id="nom" value="" required />
                    <label for="nom">Nom*</label>
                </p>
                <p>
                    <input name="email" class="text_input" type="email" id="email" value="" required />
                    <label for="email">E-Mail*</label>
                </p>
                <p>
                    <input name="objet" class="text_input" type="text" id="objet" value="" required />
                    <label for="objet">Objet*</label>
                </p>
                <p style="position: relative;">
                    <label for="message" class="textarea_label">Message*</label>
                    <textarea name="message" class="text_area" cols="40" rows="7" id="message" required></textarea>
                </p>
                <p>
                    <input type="submit" value="Envoyer" class="button">
                </p>
            </fieldset>
        </form>
    </div>
</div>