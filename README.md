# html-forms

<fieldset>
					<legend>Code information</legend>
					<p>
						<label for="Code">Code:</label>
						<select name="Code" id="Code">
							<optgroup label="script">
								<option value="html">HTML</option>
								<option value="css">CSS</option>
								<option value="js">JavaScript</option>
							</optgroup>
							<optgroup label="coding">
								<option value="java">Java</option>
								<option value="python" selected>python</option>
							</optgroup>
						</select>
						
					</p>
					<p>
						<label for="Code">Code multiple:</label>
						<select name="Code" id="Code" multiple size="5">
							<optgroup label="script">
								<option value="html">HTML</option>
								<option value="css">CSS</option>
								<option value="js">JavaScript</option>
							</optgroup>
							<optgroup label="coding">
								<option value="java" selected>Java</option>
								<option value="python">python</option>
							</optgroup>
						</select>
					</p>
					<p>
						<label for="content">Code easy:</label>
						<input type="text" name="content" id="content" list="content-list">
						<datalist id="content-list">
							<option value="html">
							<option value="css">
							<option value="js">
							<option value="java">
							<option value="python">

							</datalist>
					</p>
				</fieldset>
