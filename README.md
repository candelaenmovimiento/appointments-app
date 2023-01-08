You may also want to add README.md at this point to remind yourself how to run tests and
how to build the application.

<!-- donde pito se importaba act?? en reactTestExtensions !!

los errores empezaron cuando cambie la constante para renderizar el nombre de cada cliente, esta bien colocada la modificacion, o hay que seguir con el error varios tests para corregirlo?
updt deshice esa modificacion pq no se corregia y atrasaba los siguientes tests.
ahora:  expect(document.body.textContent).toContain("Ashley");
pagina 62 cambiar de: expect(appointmentTable().textContent).toContain("Ashley");
a: expect(appointmentTable()).toContainText("Ashley");
 ahora funciona: agregar constante en la test suite
 const appointmentTable = () =>
    document.querySelector(
      "#appointmentView > table"
    );
estaba en el repo de la clase 2 pero en el libro nunca se define?

en el test de toContainText.test: it("returns a message that contains the source line if negated match" cambie en la linea 44 de
`expect(container).not.toContainText("text to find")` 
a
`expect(element).not.toContainText("text to find")`
porque fallaba el test
bueno en el repo estaba con esta correccion, dejo esta nota por las dudas

expect().toContainText();


MODIFICAR ASI:
    const listElement = element("ol");
    expect(listElement).not.toBeNull();

    expect(element("ol")).not.toBeNull();

 -->
