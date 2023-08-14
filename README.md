# nodejs-homework-01

Contacts list
 https://monosnap.com/file/wr61CtGaNK7ozf1JgHBGux91uYaTAZ

Get contact by id
 https://monosnap.com/file/Ewh2ZS7lzMFp72xTO0DnGngRKBHdjB

Add contact
 https://monosnap.com/file/wprOUdlkmrctTHJCQFlczRYmcDcdEC

Remove contact by id
 https://monosnap.com/file/bjgSJ9KYWAtPPg7Uytqy4swve8NYNS

<!-- =================================== -->

<!-- contacts.js -->
<!-- const updateById = async (id, { name, email, phone }) => {
  const contacts = await listContacts();
  const contaktId = String(id);
  const index = contacts.findIndex((contact) => contact.id === contaktId);
  if (index === -1) {
    return null;
  }
  contacts[index] = { id, name, email, phone };
  await updateContacts(contacts);
  return contacts[index];
}; -->

<!-- =================================== -->

<!-- index.js -->
<!--     case "update":
      const updatedContact = await contacts.updateById(id, {
        name,
        email,
        phone,
      });
      console.log(updatedContact);
      break; -->

<!-- invokeAction({
  action: "update",
  id: "105f55d9-af6e-4665-aee6-9321ec89c408",
  name: "Natalia",
  email: "nbb@gmail.com",
  phone: "12345678",
}); -->

<!-- ============================= -->

<!-- // invokeAction({ action: "list" });
// invokeAction({ action: "get", id: "5" });
// invokeAction({
//   action: "add",
//   name: "Natala",
//   email: "nb@gmail.com",
//   phone: "123456",
// });
// invokeAction({
//   action: "remove",
//   id: "105f55d9-af6e-4665-aee6-9321ec89c408",
// }); -->
