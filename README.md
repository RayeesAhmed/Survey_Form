<!DOCTYPE html>
<html>
    <head>
        <title>Survey Form</title>
    </head>
    <h3>Student Survey Form</h3><hr>
    <form>
        <body>
        <p>Name: <input type="text" name="Student Name"></p>
        <p>Phone Number: <input type="tel" name="Phone Number"></p>
        <p>E-mail_ID: <input type="email" name="Email_Id"></p>
        <fieldset>
            <legend>Select Gender</legend>
            <p><input type="radio" name="Gend" value="Male">Male</p>
            <p><input type="radio" name="Gend" value="Female">Female</p>
        </fieldset>
        <fieldset>
            <legend>Special Activities</legend>
            <p>NCC:<input type="checkbox" name="extras" value="NCC"NCC</p>
            <p>NSS:<input type="checkbox" name="extras" value="NSS"NSS</p>
            <p>Sports:<input type="checkbox" name="extras" value="Sports"Sports</p>
        </fieldset>
        <p>Select Group :
            <select name="Group">
                <Option value="Selected"=Selected>Select Group</Option>
                <option value="B.Com">B.Com</option>
                <option value="BBA">BBA</option>
                <option value="B.Tech">B.Tech</option>
                <option value="Life Science">Life Science</option>
            </select>
        </p>
        <p>Suggestions:
            <textarea name="Comments" maxlength="500"></textarea>
        </p>
        <p><input type="submit" name="submit" value="submit">
        <input type="reset" name="reset" value="reset">
        </p>
    </form>
</body>
</html>
