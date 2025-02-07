---
title: Entry Point
cssclasses:
  - wide-page
banner_lock: true
banner_y: "0"
banner: "https://mir-s3-cdn-cf.behance.net/project_modules/fs/7e3d5e81488145.5d050548d72a7.jpg"
sticker: lucide//home
---

# Pagina Casa

> [!multi-column]
>
> > [!tip] Trabalho
> > 
> > - [[Notas/Index|Notas Diárias]]
> > - Gerar critérios de aceitação
> > - Agora gere os casos de testes
> > 
> >
>
> > [!Info] Pessoal
> >
> > 
> > 
> > 
> > 

> >   

 > [!Command] Comandos 
> ```dataview
LIST text.text
FROM ""
FLATTEN file.lists AS text
WHERE contains(text.text, "#commands")
> ```


> [!multi-column]
>
> > [!blank-container]
> >
> > ## Backlog 🚧
> >
> > ```dataview
> >  TABLE WITHOUT ID link(file.link, title) AS "File",
> >    bar AS "Status" FROM #todo OR #backlog AND !#dailynote AND !#template AND -"templates" SORT file.ctime LIMIT 10
> > ```
>
> > [!blank-container]
> >
> > ## Recently Created 🐣
> >
> > ```dataview
> >  TABLE WITHOUT ID link(file.link, title) as "File", length(file.inlinks) AS "Mentions"
> >  FROM "" SORT file.ctime DESC LIMIT 10
> > ```
>

